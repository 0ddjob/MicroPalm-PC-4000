# Micro Palm Computers PC/4000
The PC/4000 (and PC/5000) are MS-DOS compatible handheld computers running on an [80C88](/Pictures/Micro_Palm_80C88.jpg).  The PC/4000 comes with 256KB of RAM and 512KB of "virtual disk" storage, and has a 20x8 character, 120x64 graphics capable, backlit LCD.  They run on three C-size batteries (alkaline or rechargeable NiCd).<br>  
It has a single [50-pin DD50 socket](/Pictures/Micro_Palm_DD50_interface.jpg) through which it can support the items below.<br>

According to the demo program:
- two RS232 ports (although it has four MAX232s ... ?)
- one parallel port (hi-speed, two way)
- 256KB system RAM
- two internal 256KB modules for storage
- 20x8 backlit LCD, 80x25 virtual PC screen buffer
- MicroSoft ROM DOS ver. 2.25
- IBM-PC compatible BIOS
- MS-DOS command shell

Options included:
- supertwist LCD
- removable modules (in PC/5000)
- internal modem
- bar code wand
- communication cradle
- portable printer

![PC4000](/Pictures/Micro_Palm_PC4000.jpg)

## [Documentation](/Documents)
Unfortunately I don't have much documentation.  I do have the [READ.ME](/Documents/README.txt) that came on the Utilities Disk (SW10015) and a four-page leaflet [(MC10041)](/Documents/MicroPalm_PC4000_Important_Information_MC10041.pdf).
<br> <br>
It would be great to find the following:<br>
- PC/5000 User's Guide (MC10033),
- PC/5000 Technical Reference Manual (MC10034),
- MS-DOS User's Guide (MC10035), and
- MS-DOS Programmer's Reference (MC10036).

I found a [German article from 1992](http://www.cowo.de/a/1133979) - it seems to be announcing a reseller in Germany:

> With the models "PC/3000", "PC/4000" and "PC/5000" Technitron presents a family of MS-DOS PCs in pocket size. The computers come from Micro Paim Computers and are often used for meter reading, according to the Munich provider,

> The most powerful PC/5000 variant works with an 80C80 (sic) processor and a 256 KB system memory. In the PC/4000 version, the main memory is also 256 KB, a maximum of 704 KB of memory can be realized on both devices. In addition, disk storage modules with capacities of 128 KB, 256 KB, 512 KB or 1024 KB are available. All computers have a ROM bios and are compatible with IBM PCs. Applications can therefore be developed on a conventional PC and then transferred to the portable system. Programming languages such as Basic, Cobol, C, Pascal or Dbase can be used. According to Technitron, the user can make extensions to the PC/5000 model via plug-in modules. For example, an asynchronous modem, interfaces and RAM memory are offered. The LC display of the PCs works backlit, with two versions available: a standard screen for extreme temperatures (from about -30 degrees Celsius to about 65 degrees Celsius) and a more readable "Supertwist" display for areas of application where the temperature fluctuations are lower (from about -10 degrees Celsius to about 48 degrees Celsius). The display takes place in eight lines with 20 characters each. Graphics are displayed with 120x64 pixels.

> As the Munich company reports, the keyboard is protected against weather influences. The sealed buttons are positioned in such a way that they can also be operated with gloves.

## [Software](/Software)
My machine came with a [Utilities Disk](/Software/MicroPalm_Utilities_Disk_SW10015.zip)<br>

![Utilies Disk](/Software/MicroPalm_Utilities_Disk_SW10015.jpg)

## [Firmware](/Firmware)
The machine has two ROM sockets. It appears one is for diagnostic routines and the other is the BIOS/MS-DOS.<br>
Both have been dumped.<br>
The ROMs are N27C256-2 types.<br><br>

![ROMs](/Pictures/Micro_Palm_ROMs1.jpg)

## [Pictures](/Pictures)
Photos of the machine, including interior.

## Videos
My YouTube videos.<br>
- [Micro Palm PC/4000: Part 1](https://youtu.be/sYC32jD33a0)
- [Micro Palm PC/4000: Part 2](https://youtu.be/t-Lt_9J98sY)
- [Micro Palm PC/4000: Part 3](https://youtu.be/kz60hYqgm1A)

## DD50 Breakout Board
The DD50 interface is, as far as I know, undocumented ... well, it's documented in the missing documentation.<br>

I think it includes four serial ports at least.  Anyway, looks like I'm going to have to figure the pin out the hard way, hence the breakout board.<br>

![DD50 breakout board PCB](/DD50_Breakout/DD50_Breakout_3D.png)
