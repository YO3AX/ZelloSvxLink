# ZelloSvxLink
2026 March Update: This solution is OBSOLETE.
I no longer use this solution, after latest Zello actions to get rid of legacy clients. (see https://support.zello.com/hc/en-us/articles/36830119152397-2025-Service-Changes and https://paidsupport.zello.com/hc/en-us/articles/38073102837389-Information-about-sunsetting-older-Zello-apps-August-2025)
I have rebuild the DMR to Zello RX only links using ths solution of https://github.com/mattmelling (https://github.com/mattmelling/asl-zello-bridge) with help from YO3BEE (https://github.com/bogdan790)
Other analogic only 2 way links in YO have been rebuilt using the same solution or this one https://hamlink.app/hambridge/ of YO3TCO (a spanish how to here: https://ea5gvk-dmr.zigor.es/2025/12/29/nueva-aplicacion-hambridge-para-realizar-crosslilnk-entre-zello-y-svxlink-creada-por-chris-yo3tco/)
73!
---------------------------------
If you're into Ham Radio, Svxlink and Zello, you may like this.

It's a virtual machine that can be used as a POC (PTT Over Cellular) / Network Radio (Zello) svxlink node.

You can also set it up and use it as an outerlink to Zello for any Svxlink Analogic Network Reflector.

See https://439100.ro and https://svx.439100.ro to check a live one called ZelloLink for Romania's RoLink Svxlink Analogic Ham Radio network.

All needed instructions on how to set it up for your own use can be found on the virtual machine's desktop.

To understand what it contains, how it was made and how you can replicate it from scratch if you want, check the pdf file ZelloSvxLink.pdf.

To open the machine, download it from the link and open it in Virtualbox on your PC / Server with FIle>Import Applicance.

OBSOLETE: Link to VM download (circa 4.8 GB): https://s.go.ro/zhxnh8c4

2023 Update: In the meanwhile I created also a copy of the machine that uses svxlink-usrp branch and dvswitch in order to connect Zello channel to a digital network. Future plans are to retrieve the talker info + TG from SVXLINK log and send it as a message in Zello channel. If you are interested in any of the machines please contact me and I can provide a customized (for your use case) copy of the machine, ready to run in Proxmox virtualization server (pre-requisite). In alternative you can convert the disk to anything you want and use different virtualization tool.

Test it and if you find it useful or put it into practice for your national reflector, please let me know (https://t.me/yo3ax) and why not, invite my callsign in your Zello channel. :)

73 de YO3AX

https://QRZ.com/db/YO3AX
