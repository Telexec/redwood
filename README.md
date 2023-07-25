# Poco X5 Pro (redwood)
![I_PX5P](https://raw.githubusercontent.com/Telexec/redwood/main/assests/image/px5p.jpg)

- ## Recovery

  - ### Download
  
    - #### Ramdisk
      ![I_OFRP](https://raw.githubusercontent.com/Telexec/redwood/main/assests/image/orangefox.png)
      [OrangeFox R11.1_2](https://raw.githubusercontent.com/Telexec/redwood/main/assests/recovery/OrangeFox%20R11.1_2.cpio)  
      ![I_PBRP](https://raw.githubusercontent.com/Telexec/redwood/main/assests/image/pbrp.png "PBRP 4.0")
      [PBRP 4.0](https://raw.githubusercontent.com/Telexec/redwood/main/assests/recovery/PBRP%204.0.cpio)  
      ![I_TWRP](https://raw.githubusercontent.com/Telexec/redwood/main/assests/image/twrp.png "TWRP 3.7.0_12-0")
      [TWRP 3.7.0_12-0](https://raw.githubusercontent.com/Telexec/redwood/main/assests/recovery/TWRP%203.7.0_12-0.cpio)
  
    - #### TWRP Installer
      - [twrp_abtemplate.zip](https://raw.githubusercontent.com/Telexec/redwood/main/assests/twrp_abtemplate.zip)
  
  - ### Install Tutorial (for AOSP)
    1. Download [TWRP Installer](https://github.com/Telexec/redwood/tree/main#twrp-installer) and [Ramdisk](https://github.com/Telexec/redwood/tree/main#ramdisk).
    2. Rename ramdisk (*.cpio) to **ramdisk-twrp**.cpio or **ramdisk-recovery**.cpio.
    3. Add renamed ramdisk to TWRP Installer.  
    ![I_TABI](https://raw.githubusercontent.com/Telexec/redwood/main/assests/image/installer.png)
    4. Reboot device to recovery, select **Apply Update**, then **Apply from ADB** to begin sideload.
    5. Sideload modified TWRP Installer package using ``adb sideload twrp_abtemplate.zip``.
    6. Reboot device to recovery again to verify installation.