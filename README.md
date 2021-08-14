# ASUS-X455LAB-i3-OPEN-CORE HACKINTOSH
![Screen Shot 2021-08-14 at 18 42 06](https://user-images.githubusercontent.com/18343362/129445735-db2eb1ba-1b36-4a1e-8b34-f9e41b308957.png)



# Specifications
- [x] Processor: Intel i3 Haswell
- [x] Integrated Graphics: Intel® HD Graphics 4400
- [x] Ethernet: Realtek 8111G
- [x] Audio: Conexant CX20751/2
- [x] Memory: 10 GB
- [x] Wi-Fi and Bluetooth: Qualcomm Atheros AR956x 
- [x] Touchpad: Elan
- [x] Bootloader: OpenCore


# Current Status
- [x] Processor: Intel i3 Haswell
- [x] Integrated Graphics: Intel® HD Graphics 4400
- [x] Ethernet: Realtek 8111G
- [x] Audio: Conexant CX20751/2 (Use VoodooHDA)
- [x] Memory: 10 GB
- [ ] Wi-Fi and Bluetooth: Qualcomm Atheros AR956x (need update to big sur use ATH9KFixup.kext + ATH9KInjector.kext + Lilu.kext)
- [x] Touchpad
- [x] Audio Jack
- [x] HDMI Output
- [x] VGA Output
- [x] attery
- [x] NVRAM
- [x] macOS Recovery
- [ ] Card Reader (not tested)
- [x] F1 Sleep key
- [x] F3 and F4 Backlight keys
- [x] F5 and F6 Brightness keys
- [x] F9 Touchpad key
- [x] F10, F11 and F12 Audio keys
- [ ] Camera (Not Tested)


# Instalation
- Download Mac OS image from Olarilla Vanila Images https://www.olarila.com/topic/6278-olarila-vanilla-images/
- Create image and don't forget to format GPT to your instalattion disk. I use https://sourceforge.net/projects/win32diskimager/ for create installation disk (only windows). can use other application like rufus
- And format disk to exFat. I use https://www.partitionwizard.com/free-partition-manager.html Mini tool partition wizard
- Please read this Guide before installation to check hardware support https://dortania.github.io/Anti-Hackintosh-Buyers-Guide/Motherboard.html#audio
- And read this https://dortania.github.io/OpenCore-Install-Guide/ktext.html for check KEXT. You can explore in google if there's have another recommended KEXT for your hardware
- setup config list
Config List Haswell:
https://dortania.github.io/Getting-Started-With-ACPI/ (SSDT)
https://dortania.github.io/OpenCore-Install-Guide/config-laptop.plist/haswell.html#acpi
- ProperTree Master to edit config list
- SMBIOS to generate hardware serial number 


Please read https://dortania.github.io/OpenCore-Install-Guide/ before start installation. I'm start from `Adding the base OpenCore files` because I create Installation Disk directly from Olarila  

* Note: If want upgrade to BigSur need update that OpenCore to 0.7.x
