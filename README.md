# OpenCore HP Elitebook 2570p
# Big Sur Updated
<img src="https://github.com/acidanthera/OpenCorePkg/blob/master/Docs/Logos/OpenCore_with_text_Small.png" width="200" height="48"/>
 
 #EFI Folder for Elitebook 2570p

-For install media Big Sur you only need: https://github.com/ruben-p/OpenCore-2570p/releases

- HP Elitebook 2570p
- Intel i5 3320M
- SMBIOS MacBook11.1 *Big Sur compatibility *Change your serial with OpenCore Configurator or Plist/Text Editor
- Broadcom WIFI

#Custom Logo
- Mount EFI Partition
- Rename partition to HP_TOOLS
- Copy /Hewlett-Packard Folder
- Reboot and enable in Bios custom logo.

#HiDPI Big Sur
- https://github.com/mlch911/one-key-hidpi
- Download zip
- extract & run hidì.command. 1 Enable, 3 MacBookPro icon
- 6 Manual: 1920x1080 1600x900 1366x768
- reboot & select new resolution 1600x900

#BIOS:
- UEFI (CSM Disabled)
- Fastboot Disable

#STATS
- All working.*
- Intel HD4000.
- Battery Indicator.
- Bluetooth.
- Network.
- Wifi.
- Sound.
- Set powermanagement for this CPU with CPUFriend.kext.
- Chime Boot and sounds. *sounds disabled (PickerAudioAssist)
- GUI icons opencore
- Boot Windows & Mac
- Function keys Fn+key (Volume, Brightnes...)


# SD CardReader *Install HSSDBlockStorage.kext & JMB38X.kext to /L/E/
 - Reboot recovery
 - Open Terminal. 
 - csrutil disable
 - Reboot to the SSD then Install [Kext☞ HSSDBlockStorage.kext, JMB38X.kext](https://drive.google.com/file/d/1nBwUaRkyXYLlJBbbEBP0DPxODYif9k1X/view?usp=sharing) with ☞ [Kext-Droplet-Big Sur](https://github.com/chris1111/Kext-Droplet-Big-Sur)
- Before reboot, you have to allow JMicron on Security allow software - Before reboot, you have to allow JMicron on Security allow software


<a href="https://imgur.com/fvAgXUG"><img src="https://i.imgur.com/fvAgXUG.png" title="source: imgur.com" width="600"/></a>
