# Hackintosh-Aspire Acer E1-472g
This is my complete EFI folder to be used for hackintosh on Acer E1-472g notebook with multibooting:
- macOS High Sierra 10.13.6
- macOS Mojave 10.14.x
- macOS Catalina 10.15 and
- Windows 10 Pro

# Notebook Specs
 Aspire Acer E1-472g
 - Model: Acer Aspire E1-472G 2013
 - CPU: Intel Core i5-4200U (4) @ 2.30GHz (4nd Gen)
 - Chipset: Intel® Express Chipset
 - GPU: Intel HD 4200
 - eGPU : Nvidia GT820M
 - RAM: 12GB DDR3 @ 1600MHz (upgradable to 16GB)
 - Storage SSD : Samsung SSD 840 Evo 120 GB
 - Storage HDD: 500GB SATA @ 5400rpm (GUID Partition Table)
 - Audio: Realtek ALC282 HD Audio Controller
 - Wifi : ATheros AR956x + Bluetooth
 - Ethernet: Realtek RTL8168 PCI Express Gigabit Ethernet Controler
 - Touchpad : Elan 12C Interface
 - Display Size : 14 Inch 16:9 HD (1366x768) LED
 - Card Reader : RTS5289
 - USB port : 2 x USB 2.0 dan 1 x USB 3.0
 - Boot Mode : UEFI
 - Display Output: HDMI and VGA
 - Camera : WebCam
 - Battery : 4-Cell @2500 mA 56Wh Lithium-ion Battery
 - BIOS: Ver. 1.06 (Acer).


# EFI Contains
 - Clover Bootloader binary, config.plist, drivers for uefi, themes, etc..
 - Patched ACPI Tables (DSDT-SSDT) for Graphics, Audio, Wifi, Ethernet, Battery, etc..
 - 3rd party kexts for working devices under Mac OS X 10.11.6 upto macOS Mojave 10.15.x
 
# What Worked
- QE/CI Graphics Of IGPU IHD 4400
- Restart, Sleep and Shutdown
- Wifi
- Internal Speaker, Headphone audio and Internal Mic
- Output Audio ALC282
- Brightness 
- FN + Brightness Button Up / Down
- HDMI Output
- HDMI Audio
- Touchpad
- Keyboard
- All Port USB (USB 3.0 full speed)
- Bluetooh (Need boot to Windows first and reboot to mac)

# Not Worked / Bugs
- NVIDIA GT820M (NVIDIA Optimus is not supported by Hackintosh)
- Etc
