# Monster-Tulpar-T7-V13.1-OC-Hackintosh
This repository includes an opencore efi folder to run on a clevo based 7th gen i7 monster branded laptop.

cpu: i7 7700hq
gpu: hd graphics 630 / gtx 1060 mobile (deactivated)

OS: MacOS Big Sur

Product Page: https://www.monsternotebook.com.tr/tulpar/monster-tulpar-t7-v13-1/


What's Working?
--
- CPU Power Management (full 45W, but tuned for MP pro style with CPUFriend.kext)
- Intel Wifi
- Synaptics Touchpad
- Screen brightness control
- GPU acceleration
- SATA & NVMe SSD
- Battery Status
- Sound - Mic
- Webcam
- Sound up and down keys

What's NOT working?
--
- Nvidia GPU thus HDMI and 2nd mini DP port
- Birhtness up and down keys
- Keyboard backlight control
- AirDrop
- Native XCPM --> AppleXcpmCfgLock setting on OpenCore

Not Tested
- Hibernation (but probably fine)

NOTE
--
- Dualbooting with windows certainly guarantees you a blue screen! That is because OpenCore trys to inject every patch for every OS possible on startup.
