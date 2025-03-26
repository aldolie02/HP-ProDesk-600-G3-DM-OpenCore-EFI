<h1><b>HP ProDesk 600 G3 DM OpenCore v1.0.4</b></h1>

- <b>Keep In Mind!</b><br>
This EFI also works for any other Mini PC with similiar build: ThinkCentre, etc as long as it's Kaby Lake.<br>
You just need to tweak the kexts with whatever hardware you have. <br>
(for example, you'll have to add itlwm for Intel WLAN Cards).<br>

---
- <b>Things You Need To Do:</b><br>
1. <b>(Required)</b> Generate iMac18,1 SMBIOS with SMBIOSGen, and fill those values under [PlatformInfo > Generic].<br>Fill the ROM value with your Ethernet MAC Address for proper iMessage support.<br>
> - P.S. I've tried Macmini8,1 SMBIOS and performance tanked since it's optimized for Coffee Lake, not Kaby Lake.<br>
2. <b>(Sonoma++)</b> If you're using Broadcom WLAN/BT cards, you have to use OCLP.<br>
3. <b>(Important)</b> If you're not using HP ProDesk 600 G3, you'll need to create your own UTBMap.kext using this <a href="https://github.com/USBToolBox/tool">tool</a>,<br> 
otherwise your USB ports ain't gonna work properly since you'll have different port layout


---
- <b>My Specs:</b><br>
1. CPU: Intel Core i5-7500T<br>
2. GPU: Intel HD Graphics 630<br>
3. RAM: DDR4 16GB 2400 MHz<br>
4. Audio: Conexant CX20632 Audio<br>
5. Ethernet Card: Intel I219-LM Ethernet<br>
6. Bluetooth: Cheap Chinese CSR 5.0 Bluetooth Dongle (0A12_0001 = 2578_1)


---
- <b>BIOS Settings</b> <br>
<a href="https://github.com/ivan19871002/HP-ProDeks-680-G3-MT-Hackintosh/blob/main/HP%20EliteDesk%20800%20G4%20Mini%20BIOS%20Configuration.pdf">Credits to Qiwu Huang (@ivan19871002)</a>
---
- <b>Tested Working On:</b><br>
  Latest Sonoma ~~(Recommended)~~<br>
  Latest Ventura<br>
  Latest Monterey <b>(Actually Recommended)</b>


~~I'm currently trying out Ventura, but I optimized this EFI for Sonoma.<br>
Tbh, I hate Ventura. I'll upgrade back to Sonoma because it performs better for me.~~

My curiousity grew on Monterey, I tried it out, and I swear I'll keep on using this MacOS version no matter what.<br>
App Support kinda sucks, but hey you can still find Older Version of apps that still supports Monterey.<br>

If you wanna use something newer than Monterey, just jump to Sonoma as it's way better than Ventura is.<br>

><b>Apple</b> intentionally not focusing on Stability when building <b>Ventura</b>, because it's all about restructuring the way MacOS works.<br>
><b>Ventura</b> sits between the _'last Intel focused'_ <b>Monterey</b>, and _'the new and stable'_ <b>Sonoma</b>.<br>
>
>This hit my nostalgia nerves! you know why? I witnessed the hate <b>Microsoft</b> got for <b>Windows Vista</b>!<br>
>It's an understatement to say that <b>Apple</b> was a little inspired by the way <b>Microsoft</b> handled their bad reps.
>
><br><b>Ventura</b> is __Apple__'s interpretation of __Windows Vista__. How?<br>
>1. They got released right after their 'user favorite' version: <b>Monterey</b> & <b>Windows XP</b>,<br>
>2. The only reason they exist is specifically to collect as many complaints from customers as possible,<br>
>3. They don't bother fixing them, because they gon' release these fixes not as an Update, but as a new OS version.<br>
>4. Lo and behold, another 'user favorite' version was born: __Sonoma__ and __Windows 7__.
>
><br>If these companies keep on doing this capitalist move as their way of operating internally,<br> these 'sins' will eventually haunt their credibility in the future. 

Love from Indonesia!
Support Ukraine and Palestine!

