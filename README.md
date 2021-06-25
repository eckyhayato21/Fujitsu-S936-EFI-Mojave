# Fujitsu-S936-EFI-Mojave
Here my EFI Configuration for

FUJITSU S936 / M

Technical Specs :
- Processor : Intel(R) Core(TM) i5 6300U @ 2.4Ghz
- iGPU : Intel HD Graphics 520
- Wireless : Intel 8260
- Audio : Realtek ALC255
- Screeen size : 13.3 LED Full HD 1920x1080
- Memory : RAM 12GB (4GB onboard + 8GB DDR4 2133 MHz)
- Storage : SSD M2 128GB
- BIOS : H20 INSYDE VER
- Connection : HDMI, 3x USB 3.0, VGA, SD Card Reader
- etc.

Installed Mac OS 10.14.5 A.K.A MOJAVE 

What's Working :
- Native Power Management
- Intel HD Gaphics 520 QE/CI
- Wifi ( Aiportitlwm.kext used as plugin on IO8211Family.kext )
- Bluetooth ( IntelBluetoothFirmware.kext & IntelBluetoothInjector.kext)
- USB 3.0
- Trackpad With gesture (VoodooPS2Controller.kext)
- Brightness (Patch SSDT)
- HDMI Port
- Shutdown / Restart / Sleep
- Battery Status (VirtualSMC.kext & SMCBatteryManager.kext)
- etc.

What's Not Working and Not tested yet
- Airdrop ( not tested yet )
- VGA Port ( not tested yet )
- Audio port 3.5mm ( not tested yet )
- SDCard Reader
- Fingerprint

EFI Folder :
- <a href"https://drive.google.com/file/d/18GI8pdItJ82WrnPGolAdc3CToPBEJNst/view?usp=sharing">EFI Clover</a>

References & Credits :
- <a href="http://google.co.id">Your Master of Knowledge</a>
- <a href="https://www.olarila.com/topic/5139-mojave-olarila/">OLARILA Images 10.14.5 mojave</a>
- <a href="https://www.tonymacx86.com/threads/guide-laptop-backlight-control-using-applebacklightfixup-kext.218222/">SSDT patch for Brightness Fix by RehabMan</a>
- <a href="https://github.com/acidanthera/AppleALC">AppleALC for audio fix by acidanthera</a>
- <a href="https://openintelwireless.github.io/itlwm/Installation.html#airportitlwm">AirportItlwm for Intel Wireless (WIFI & Bluetooth) fix by OpenIntelWireless project</a>
- <a href="https://github.com/acidanthera/VoodooPS2/releases">VoodooPS2Controller for Keyboard & Trackpad fix by acidanthera</a>
- <a href="https://github.com/acidanthera/virtualsmc/releases">VirtualSMC by acidanthera</a> 
