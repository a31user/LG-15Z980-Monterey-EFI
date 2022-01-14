# LG-15Z980-Monterey-EFI
An EFI made for 15Z980 LG GRAM devices supporting Catalina up to Monterey lastest.
Due to the github capacity issues, I had zipped it into a 7z file.

Has a little problem. Please refer to this problem issue report written by myself.
https://github.com/a31user/LG-15Z980-Monterey-EFI/issues/4

You are able to use...
1. Battery
2. Bluetooth
3. WIFI (Native) -- *PROBLEM REPORTED* MAYBE DON'T SUPPORT 5GHZ
4. Sleeping
5. Touchpad
6. USB ALL PORTS WORKING (MAPPED) -- Changed to UTBMAP.KEXT+USBTOOLBOX.KEXT TO MAKE USERS CHANGE SMBIOS EASILY WITHOUT CHANGEING THE USB MAPPING KEXT PLIST FILE
7. Brightness Control
8. And Everything ETC
9. HDMI (WOULD WORK, BUT UNTESTED)

You are not able to use...
1. 5GHZ WIFI (MINE WORKS BUT PROBLEM IS REPORTED)
2. IPHONE HOTSPOT (UNTESTED BY MYSELF DUE TO I DON'T HAVE A LTE APPLE DEVICE, BUT PROBLEM IS REPORTED)

Untested
1. Thunderbolt (Added IOELECTRIFY.KEXT and SSDT-DTPG but I couldn't test it

Please leave bug or anything wrong in the issues page.

+Add
Please change the smbios with GenSMBIOS before you use it.
If you are using catalina or big sur, plesase change airportitlwm version, and intelbluetoothfirmware+bluetoolfixup to intelbluetoothfirmware+intelbluetoothinjector.

This EFI's ACPI PART is made refered to https://github.com/suzuke/LG-Gram-13z980-Opencore.

*The EFI is located in the Releases Page Attachment.*
