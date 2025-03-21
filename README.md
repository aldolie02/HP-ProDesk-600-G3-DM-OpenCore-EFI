<h1><b>HP ProDesk 600 G3 DM OpenCore v1.0.4</b></h1>

- <b>Keep In Mind!</b><br>
This EFI also works for any other Mini PC with similiar build: ThinkCentre, etc as long as it's Kaby Lake.<br>
You just need to tweak the kexts with whatever hardware you have. <br>
(for example, you'll have to add itlwm for Intel WLAN Cards).<br>

- <b>Tested Working On:</b><br>
  Latest Sonoma <b>(Recommended)</b><br>
  Latest Ventura

I'm currently trying out Ventura, but I optimized this EFI for Sonoma.<br>
Tbh, I hate Ventura. I'll upgrade back to Sonoma because it performs better for me.


---
- <b>Things You Need To Do:</b><br>
1. <b>(Required)</b> Generate iMac18,1 SMBIOS with SMBIOSGen, and fill those values under [PlatformInfo > Generic].<br>Fill the ROM value with your Ethernet MAC Address for proper iMessage support.<br>
> - P.S. I've tried Macmini8,1 SMBIOS and performance tanked since it's optimized for Coffee Lake, not Kaby Lake.<br>
2. <b>(Sonoma++)</b> If you're using Broadcom WLAN/BT cards, you have to use OCLP.<br>
3. <b>(Important)</b> If you're not using HP ProDesk 600 G3, you'll need to create your own UTBMap.kext using this <a href="https://github.com/USBToolBox/tool">tool</a> 
otherwise USB most likely won't work since you'll have different port layout


---
- <b>My Specs:</b><br>
1. CPU: Intel Core i5-7500T<br>
2. GPU: Intel HD Graphics 630<br>
3. RAM: DDR4 16GB 2400 MHz<br>
4. Audio: Conexant CX20632 Audio<br>
5. Ethernet Card: Intel I219-LM Ethernet<br>
6. Wireless LAN Card: Broadcom BCM943142Y


---
- <b>BIOS Settings</b> <br>
<a href="https://github.com/ivan19871002/HP-ProDeks-680-G3-MT-Hackintosh/blob/main/HP%20EliteDesk%20800%20G4%20Mini%20BIOS%20Configuration.pdf">Credits to Qiwu Huang (@ivan19871002)</a>


