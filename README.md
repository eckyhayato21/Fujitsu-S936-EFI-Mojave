<body>

<h1>Fujitsu-S936-EFI-Mojave</h1>
  
  <h2>Technical Specs :</h2>
  
<p>- Processor : Intel(R) Core(TM) i5 6300U @ 2.4Ghz</p>
<p>- iGPU : Intel HD Graphics 520</p>
<p>- Wireless : Intel 8260</p>
<p>- Audio : Realtek ALC255</p>
<p>- Screeen size : 13.3 LED Full HD 1920x1080</p>
<p>- Memory : RAM 12GB (4GB onboard + 8GB DDR4 2133 MHz)</p>
<p>- Storage : SSD M2 128GB</p>
<p>- BIOS : H20 INSYDE</p>
<p>- Connection : HDMI, 3x USB 3.0, VGA, SD Card Reader</p>
<p>- etc.</p>

<img src="https://support.apple.com/library/APPLE/APPLECARE_ALLGEOS/SP777/mojave-roundel-240.png">

<h1>Installed Mac OS 10.14.5 a.k.a Mojave</h1> 

<h2>What's Working :</h2>

<p>- Native Power Management</p>
<p>- Intel HD Gaphics 520 QE/CI
<p>- Wifi ( for Clover the Aiportitlwm.kext used as plugin on IO8211Family.kext, for OC simply put the Airportitlwm.kext on Kext Folder )</p>
<p>- Bluetooth ( IntelBluetoothFirmware.kext & IntelBluetoothInjector.kext)</p>
<p>- USB 3.0 HSxx & SSxx</p>
<p>- Trackpad With gesture (for OC pull out all plugin of VoodooPS2Controller.kext and load it separately, begin with VoodooInput.kext)</p>
<p>- Brightness (Patch SSDT-PNLF works with new built WhateverGreen.kext)</p>
<p>- HDMI Vidoe and Audio Output</p>
<p>- Shutdown / Restart / Sleep</p>
<p>- Battery Status (VirtualSMC.kext & SMCBatteryManager.kext)</p>
<p>- etc.</p>

<h2>What's Not Working and Not tested yet</h2>

<p>- VGA Port ( not tested yet )</p>
<p>- Audio port 3.5mm ( not tested yet )</p>
<p>- Airdrop</p>
<p>- SDCard Reader</p>
<p>- Fingerprint</p>

<p>EFI Folder :</p>

<p>- EFI Clover <a href="https://drive.google.com/file/d/18GI8pdItJ82WrnPGolAdc3CToPBEJNst/view?usp=sharing">Download Here</a></p>
<p>- EFI OpenCore <a href="https://drive.google.com/drive/folders/1Um5Tvx7-ocBoKjW9J15zkgW2GJ80jqhI?usp=sharing">Download Here</a></p>

<p>References & Credits :</p>

<p>- <a href="http://google.co.id">Your Master of Knowledge</a></p>
<p>- <a href="https://dortania.github.io/getting-started/">Dortania Github for Getting Sterted with OC Bootloader</a></p>
<p>- <a href="https://www.olarila.com/topic/5139-mojave-olarila/">OLARILA Images 10.14.5 mojave</a></p>
<p>- <a href="https://www.tonymacx86.com/threads/guide-laptop-backlight-control-using-applebacklightfixup-kext.218222/">SSDT patch for Brightness Fix by RehabMan</a></p>
<p>- <a href="https://github.com/acidanthera/AppleALC">AppleALC for audio fix by acidanthera</a></p>
<p>- <a href="https://openintelwireless.github.io/itlwm/Installation.html#airportitlwm">AirportItlwm for Intel Wireless (WIFI & Bluetooth) fix by OpenIntelWireless project</a></p>
<p>- <a href="https://github.com/acidanthera/VoodooPS2/releases">VoodooPS2Controller for Keyboard & Trackpad fix by acidanthera</a></p>
<p>- <a href="https://github.com/acidanthera/virtualsmc/releases">VirtualSMC by acidanthera</a></p>

</body>
