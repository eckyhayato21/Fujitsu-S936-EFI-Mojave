<h1 style="text-align:center;">Fujitsu-S936-EFI-Mojave</h1>

<h2>Technical Specs :</h2>

- Processor : Intel(R) Core(TM) i5 6300U @ 2.4Ghz
- iGPU : Intel HD Graphics 520
- Wireless : Intel 8260
- Audio : Realtek ALC255
- Screeen size : 13.3 LED Full HD 1920x1080
- Memory : RAM 12GB (4GB onboard + 8GB DDR4 2133 MHz)
- Storage : SSD M2 128GB
- BIOS : H20 INSYDE
- Connection : HDMI, 3x USB 3.0, VGA, SD Card Reader
- etc.

<img src="https://support.apple.com/library/APPLE/APPLECARE_ALLGEOS/SP777/mojave-roundel-240.png">
<h1 style="text-align:center;">Installed Mac OS 10.14.5 a.k.a Mojave</h1> 

<h2>What's Working :</h2>

- Native Power Management
- Intel HD Gaphics 520 QE/CI
- Wifi ( for Clover the Aiportitlwm.kext used as plugin on IO8211Family.kext, for OC simply put the Airportitlwm.kext on Kext Folder )
- Bluetooth ( IntelBluetoothFirmware.kext & IntelBluetoothInjector.kext)
- USB 3.0 HSxx & SSxx
- Trackpad With gesture (for OC pull out all plugin of VoodooPS2Controller.kext and load it separately, begin with VoodooInput.kext)
- Brightness (Patch SSDT-PNLF works with new built WhateverGreen.kext)
- HDMI Vidoe and Audio Output
- Shutdown / Restart / Sleep
- Battery Status (VirtualSMC.kext & SMCBatteryManager.kext)
- etc.

<h2>What's Not Working and Not tested yet</h2>

- VGA Port ( not tested yet )
- Audio port 3.5mm ( not tested yet )
- Airdrop
- SDCard Reader
- Fingerprint

EFI Folder :
- EFI Clover <a href="https://drive.google.com/file/d/18GI8pdItJ82WrnPGolAdc3CToPBEJNst/view?usp=sharing">Download Here</a>
- EFI OpenCore <a href="https://drive.google.com/drive/folders/1Um5Tvx7-ocBoKjW9J15zkgW2GJ80jqhI?usp=sharing">Download Here</a>

References & Credits :

- <a href="http://google.co.id">Your Master of Knowledge</a>
- <a href="https://dortania.github.io/getting-started/">Dortania Github for Getting Sterted with OC Bootloader</a>
- <a href="https://www.olarila.com/topic/5139-mojave-olarila/">OLARILA Images 10.14.5 mojave</a>
- <a href="https://www.tonymacx86.com/threads/guide-laptop-backlight-control-using-applebacklightfixup-kext.218222/">SSDT patch for Brightness Fix by RehabMan</a>
- <a href="https://github.com/acidanthera/AppleALC">AppleALC for audio fix by acidanthera</a>
- <a href="https://openintelwireless.github.io/itlwm/Installation.html#airportitlwm">AirportItlwm for Intel Wireless (WIFI & Bluetooth) fix by OpenIntelWireless project</a>
- <a href="https://github.com/acidanthera/VoodooPS2/releases">VoodooPS2Controller for Keyboard & Trackpad fix by acidanthera</a>
- <a href="https://github.com/acidanthera/virtualsmc/releases">VirtualSMC by acidanthera</a> 
