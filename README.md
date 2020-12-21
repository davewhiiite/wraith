# Wraith Enclosure (Specter DIY steel enclosure)
Sheet metal enclosure for a basic Specter DIY assembly
 
Link to this project:
https://github.com/davewhiiite/wraith

Link to original Specter DIY project:
https://github.com/cryptoadvance/specter-diy

Please read the whole README doc before attempting to build
your own enclosure.

# License
Distributed under the DWYL License = do what you like.
You don't have to use the docs as they are. Feel free to riff
on them. Make a product if you want. Credit me if you feel
so compelled. 

The logo uses a font called "Tron" -- located here:
https://www.fontspace.com/tron-font-f9678

If you use the logo or font for commercial purposes, 
you should pay the designer, FZ Fonts, who has the copyright.

Note: I don't claim to have any rights to the Specter title. If 
the guys at Crypto Compare don't want it up here, I'll take it
down, and call this something else.

# Disclaimer
It is assumed you are an adult, and will make responsible use
of the design. Don't break the law, and I am not responsible for any
misuse, personal financial loss, penalties, or damages that occur 
if you build your own hardware wallet. Don't be an idiot.
Use at your own risk, and as always: don't trust; verify.

# About
I designed the enclosure for my own use, but I am sharing
the design as a thank you to the Specter team and community, 
for developing such an awesome suite of open source software.  
It's a unique point in time where you can hold your keys ON HARDWARE 
YOU ASSEMBLED YOURSELF, and whatever your views on "unhosted 
wallets" are, it must be acknowledged that this is certifiably bad-ass.

# Enclosure Features
- The configuration is for just the STM32F469-DISCO plus QR scanner;
the "amnesiac" style of Specter DIY. No support for the smart card
or DIY Shield has been added (regretfully I was too lazy to get one, 
but may get one in the future).
- Enclosure includes an SD card slot (so yeah, you can save to SD)
- The only real provisions for power are via USB. Frankly,
I don't see a reason to not use the USB cable, since you can use an old
Android phone charger or a 5V USB battery pack, which are abundant
and cheap. You might fit a battery inside, but you'd want to add a switch to shut it off, 
and keep the battery's output voltage to 5-6V, since the Disco's E5V input
has a linear voltage regulator on it that will kill a 9V battery in a matter of minutes. 
- The box is made of carbon steel. Very durable.
- The enclosure has a basic metal shield that screws on to protect
the screen. This is meant to prevent scratches, cracks, or shattering.
It should be useful for long-term storage.

# Assembly Instructions
There is a complete Solidworks model and a bill of materials 
to help you get your head wrapped around how everything comes together.
The only electronics you need are the ST Micro STM32F469-DISCO
development kit, and the WaveShare QR scanner (plus USB cable/charger, micro-SD card,
misc internal connecting wires). Please use the various CAD models and gallery
images to guide you. 

# Documents 
There are (3) folders:
1. images -- gallery of the finished assembly
2. wraith-assy -- this is the complete solidworks assembly, as I imagined it.
This folder includes the original bill of materials. This directory constitutes
the "original" design.
3. as-built -- just zip up this file, send to Protocase.com, or contract
manufacturer of your choice, and say you want n quantity of these. You will notice
that there are some changes to the enclosure (relief cuts, hardware), that make
this design more manufacturable. These changes were proposed by Protocase.
In all, this is the final design for the sheet metal components.

# Purchasing Your Own
I used the services of Protocase.com to build this enclosure. Again, just zip up and
send the "as-built" folder and send to them, or the CM of your choice. Protocase
people were very easy to work with.

# Cost
In single unit quantities the assembly is very expensive ($450).
However, if you can get a few friends together then the price starts
to come down rather quickly (all-in cost for qty 10 = $150; qty 100 = $92).
You can probably do things like ditch the front cover to save more money,
or other things to "value engineer" the cost out of it.

# Misc Design details
- The finish is a gloss black powdercoat. Official name is FS 17038 Black
Full Gloss Smooth Polyester Powder. Feel free to pick your own; I also imagined 
a matte gunmetal / gray would look pretty sweet. 
- The artwork is permanently etched into the enclosure using "laser ablation." 
Lasers are, of course, demonstrably bad-ass. 
- Use black hardware to make everything match (I don't think my BOM necessarily used
 black hardware by default). Neverless, the Protocase people selected black 
 probably because they have more sense than I do.

# Outstanding Issues
1. Some deformation occurred when bending the tabs that support the
Discovery screen assembly, and so the PEM studs did not align properly
with the holes in the PCB. You may have to take a power drill to the PCB and
widen the holes like I did. That, or fix the CAD model (wah wah).

2. The QTY (4) M2x4mm screws (Item #9, McMaster Carr P/N = 97763A405) didn't get shipped
by ProtoCase with the assembly. You can either buy the ones above, or use the ones that come with 
Waveshare QR scanner (too long, IMO).

3. There's an ugly cutout in the bottom of the enclosure to accommodate the USB
connector on the bottom of the QR scanner. If you cut off the connector, you wouldn't
need to have cutout, and it would look nicer. But I left the cutout, since I 
figured maybe you didn't want to mutilate your $40 QR scanner.

4. The front cover doesn't sit 100% flat when installed. This is because the screws on one side
create tension that cause the unfastened side of the cover to lift slightly. I don't have 
a clever solution to that, but maybe you do!

# Thanks
As a pandemic hobby, learning the Specter "stack" has been a rewarding challenge. I am still
in disbelief that such a reliable multi-sig HWW solution could emerge so quickly, or smoothly. Major 
kudos to Stepan, Ben, Moritz, Kim, and the rest of you that spend hours of your personal 
time in this wormhole. Cheers, and happy new year!


