# Hackintosh Aspire E1-472G-54204G75Mnkk
This is my complete EFI folder to be used for hackintosh on Acer Aspire E1-472g notebook with multibooting:
- macOS High Sierra 10.13.6
- macOS Mojave 10.14.x
- macOS Catalina 10.15 and
- Windows 10 Pro


<img src="/IMG/Catalina.png?raw=true" alt="macOS Catalina" align="center">

--------------------------------------------------------------------------------------------

### Notebook Specs
<img src="/IMG/E1-472g.png?raw=true" alt="Acer Aspire E1-472G" align="right">
 
 Aspire Acer E1-472g
 - Model: Acer Aspire E1-472G-54204G75Mnkk 2013
 - CPU: Intel Core i5-4200U (4) @ 2.30GHz (4nd Gen)
 - Chipset: Intel® Express Chipset
 - GPU: Intel HD Graphics 4200
 - eGPU : Nvidia GT720M
 - RAM: 12GB DDR3 @ 1600MHz (upgradable to 16GB)
 - Storage SSD : Samsung SSD 840 Evo 120 GB (GUID Partition Table)
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
 - Camera : UVC Camera VendorID_1266 ProductID_46038
 - Battery : 4-Cell @2500 mA Lithium-ion Battery
 - BIOS: Ver. 2.10 (Acer).

--------------------------------------------------------------------------------------------

### EFI Contains
 - Clover Bootloader binary, config.plist, drivers for uefi, themes, etc..
 - Patched ACPI Tables (DSDT-SSDT) for Graphics, Audio, Wifi, Ethernet, Battery, etc..
 - 3rd party kexts for working devices on Mac OS X 10.15
 
 --------------------------------------------------------------------------------------------
 
### What Worked
- [x] QE/CI Graphics Of IGPU IHD 4400
- [x] Restart, Sleep and Shutdown
- [x] Wifi
- [x] Internal Speaker, Headphone audio and Internal Mic
- [x] Output Audio ALC282
- [x] Brightness 
- [x] FN + Brightness Button Up / Down
- [x] HDMI Output
- [x] HDMI Audio
- [x] Touchpad
- [x] Keyboard
- [x] All Port USB (USB 3.0 full speed)
- [x] Bluetooh (Need boot to Windows first and reboot to mac)

--------------------------------------------------------------------------------------------

### Not Worked / Bugs
- [ ] NVIDIA GT720M (NVIDIA Optimus is not supported by Hackintosh)
- [ ] Etc

--------------------------------------------------------------------------------------------

### Notes
1. macOS versions used are Retail from Mac App Store, using createinstallmedia for USB Installer
2. Platform Datas (SN, ROM, UUID) used here are ALL FAKE. So, you need to regenerate them.
3. Don't use Patched DSDT-SSDT if you have different BIOS version (need to configure config.plist - ACPI section)
4. To boot with Clover UEFI, you need to configure BIOS

### Credits
[Apple](https://www.apple.com) | [Microsoft](https://www.microsoft.com/en-us/windows) | [Clover](https://sourceforge.net/projects/cloverefiboot) | [Acidanthera](https://github.com/acidanthera) | [Rehabman](https://github.com/RehabMan/Laptop-DSDT-Patch) | [Andres ZeroCross](https://github.com/andreszerocross) | [Badruzeus](https://github.com/badruzeus) | [InsanelyMac](https://www.insanelymac.com/forum), | [Olarila](http://olarila.com/forum) and [OSXLatitude](https://osxlatitude.com/forums) Forum | <b>Other devs</b> who aren't mentioned.
