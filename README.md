# Resources for Poco X5 Pro
![Poco X5 Pro](https://raw.githubusercontent.com/Telexec/redwood/main/assests/image/px5p.jpg "Poco X5 Pro")
## Recovery Ramdisk

### Download
[![OrangeFox](https://raw.githubusercontent.com/Telexec/redwood/main/assests/image/orangefox.png "OrangeFox R11.1_2")](https://raw.githubusercontent.com/Telexec/redwood/main/assests/recovery/OrangeFox%20R11.1_2.cpio)[![PBRP](https://raw.githubusercontent.com/Telexec/redwood/main/assests/image/pbrp.png "PBRP 4.0")](https://raw.githubusercontent.com/Telexec/redwood/main/assests/recovery/PBRP%204.0.cpio)[![TWRP](https://raw.githubusercontent.com/Telexec/redwood/main/assests/image/twrp.png "TWRP 3.7.0_12-0")](https://raw.githubusercontent.com/Telexec/redwood/main/assests/recovery/TWRP%203.7.0_12-0.cpio)
### Install Tutorial (for AOSP)
1. Download [TWRP A/B Installer Zip Template](https://raw.githubusercontent.com/Telexec/redwood/main/assests/twrp_abtemplate.zip) and [Recovery Ramdisk](https://github.com/Telexec/redwood/tree/main#download).
2. Rename ramdisk (*.cpio) to **ramdisk-twrp**.cpio or **ramdisk-recovery**.cpio.
3. Add renamed ramdisk to zip template.  
![TWRP A/B Installer](https://raw.githubusercontent.com/Telexec/redwood/main/assests/image/installer.png "TWRP A/B Installer")
4. Reboot device to recovery, select **Apply Update**, then **Apply from ADB** to begin sideload.
5. Sideload modified TWRP A/B Installer package using ``adb sideload twrp_abtemplate.zip``.
6. Reboot device to recovery again to verify installation.