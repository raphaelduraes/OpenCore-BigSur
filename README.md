# OpenCore-BigSur
OpenCore folder for MacOS BigSur on DELL XPS9570

##Caveats
- For Intel Wifi card to work without hardcoding SSIDs/Passwords install Heliport - https://github.com/OpenIntelWireless/HeliPort
- USB-C hotplug for dual screen is broken by `IntelBluetoothFirmware.kext` and/or `IntelBluetoothInjector.kext` entries on `plist.config`. It works fine pluging into the HDMI port though.
- Be sure the `BOOT` folder in EFI partition points to OC folder.
