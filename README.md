<h1><b>HP ProDesk 600 G3 DM OpenCore v1.0.4</b></h1>

- <b>BIOS Settings</b> <br>
<a href="https://github.com/ivan19871002/HP-ProDeks-680-G3-MT-Hackintosh/blob/main/HP%20EliteDesk%20800%20G4%20Mini%20BIOS%20Configuration.pdf">Credits to Qiwu Huang (@ivan19871002)</a>

---
- <b>Keep In Mind!</b><br>
This EFI also works for any other Mini PC with similiar build: ThinkCentre, etc as long as it's Kaby Lake.<br>
You just need to tweak the kexts with whatever hardware you have. <br>
(for example, you'll have to add itlwm for Intel WLAN Cards).<br>

---
- <b>My Specs:</b><br>
1. CPU: Intel Core i5-7500T<br>
2. GPU: Intel HD Graphics 630<br>
3. RAM: DDR4 16GB 2400 MHz<br>
4. Audio: Conexant CX20632 Audio<br>
5. Ethernet Card: Intel I219-LM Ethernet<br>
6. Wireless LAN Card: Broadcom BCM943142Y (Useless)

---
- <b>Things You Need To Do:</b><br>
1. <b>(Required)</b> Generate iMac18,1 SMBIOS with SMBIOSGen, and fill those values under [PlatformInfo > Generic].<br>Fill the ROM value with your Ethernet MAC Address for proper iMessage support.<br>
> - P.S. I've tried Macmini8,1 SMBIOS and performance tanked since it's optimized for Coffee Lake, not Kaby Lake.<br>
2. <b>(Sonoma++)</b> If you're using Broadcom WLAN/BT cards, you have to use OCLP.<br>
3. <b>(Important)</b> If you're not using HP ProDesk 600 G3, you'll need to create your own UTBMap.kext using this <a href="https://github.com/USBToolBox/tool">tool</a> 
otherwise USB most likely won't work since you'll have different port layout

---
- <b>Tested Working On:</b><br>
__#1   Latest Monterey (Champion)__ <br>
  #2   Latest Sonoma <br>
  DNF Latest Ventura <br><br>
~~I'm currently trying out Ventura, but I optimized this EFI for Sonoma.<br>
Tbh, I hate Ventura. I'll upgrade back to Sonoma because it performs better for me.~~ <br><br>
I intended to try out __Monterey__ just to see how things fare on this OS.<br>
Surprisingly, I feel like I'll have to delay my upgrade to __Sonoma__ for a few months.<br>
I'm quite comfy with how snappy this little beast is feeling rn. <br><br>
If you just wanna do some browsing, and you don't require the latest and greatest app supports, pick __Monterey__.<br>
However if you want something newer than __Monterey__, just go directly to __Sonoma__. <br>

---
- ___"Why?"_ you might ask..__ <br>
__Ventura__ is essentially a spitting image of __Windows Vista__.<br>
They're specifically designed to collect as many errors as possible from their userbase.<br>
That data then gets collected and as they repair most of them, they're packaging it as the new OS __Sonoma__, not an Update.<br><br>
The cycle is indeed true, and I have a nickname for it: ___"CAPITALISMove"___<br>
We all agreed that __Monterey__ and __Windows XP__ is one of the most beloved OS version (a.k.a last known good OS),<br>
Then __Ventura__ and __Windows Vista__ deliberately came as the 'transitional' or 'sacrificial' version. Of course everyone hates it.<br>
Finally, our hero has come, __Sonoma__ and __Windows 7__.<br><br>
Classic Bait-and-Switch situation, isn't it?<br>
(this is why I hate western companies. especially the established ones)




