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
> - P.S. I've tried Macmini8,1 SMBIOS and performance tanked since it's optimized for Coffee Lake, not Kaby Lake.
2. If you're gonna use this EFI for Sonoma, Don't forget to use Broadcom Kexts as Apple dropped native support for Broadcoms on Sonoma.


---
- <b>My Specs:</b><br>
1. CPU: Intel Core i5-7500T<br>
2. GPU: Intel HD Graphics 630<br>
3. RAM: DDR4 16GB 2400 MHz<br>
4. Audio: Conexant CX20632 Audio<br>
5. Ethernet Card: Intel I219-LM Ethernet<br>
6. Wireless LAN Card: Broadcom BCM943142Y
