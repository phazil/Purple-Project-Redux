# Purple Project Redux

A recreation of @TheTrain24's Purple Project seen here:
[Reference Posts](https://github.com/phazil/Purple-Project-Redux/blob/main/Docs/Inspiration%20Posts.md)

This started out as a post graduation project (someone in biology hire me pls) to explore deeper into the hobbies I was already interested in. Did all of the CAD/KiCAD work myself, and also because I missed out on the originals Train posted. Lots was learned here, and documenting it all isn't as fun as making it but I guess it's necessary lol. 

This is my attempt to recreate Train's version, however there are differences. There is no custom wiring terminal pcb, it's not double stacked FR4 for both front/back panel, and there's no usage of low profile OSBMXs. I used a right angle header soldered onto a Basic Breakout Board running GP2040-CE along with a 20-pin wiring harness. There is some soldering involved in this to get the menu panel working however it is sequential and there's only 1 ground line needed. The single panel do not flex at all with the increase inside area of the 3D prints. you would have to try to push down really hard on the center of the panels to even see any sort of flex. Any low profile buttons that fit within a 20mm tall enclosure should work too.

As regards for making and selling, I do not think this is the most efficient way to go about it. The original project I am pretty sure was scrapped due to how expensive FR4 panels end up being. Using laser cut acrylic is probably more efficient for anything of the sorts. Total cost for making 5 of these is about $750 with the materials I chose, so around $160 each is close to breaking even. This does not at all account for the time needed to print parts or build this.

If you need any help or are even thinking about making this please contact me on Discord! I'd be willing to help. @phazil

![Showcase Test](https://github.com/phazil/Purple-Project-Redux/blob/main/Images/Personal%20Builds/20241123_215220454_iOS.jpg)
![Showcase Test 2](https://github.com/phazil/Purple-Project-Redux/blob/main/Images/Personal%20Builds/20241123_140203437_iOS.jpg)

## Repository Directory:
* [Full Readme](https://github.com/phazil/Purple-Project-Redux/blob/main/README.md)
	* [Reference Posts](https://github.com/phazil/Purple-Project-Redux/blob/main/Docs/Inspiration%20Posts.md)
	* [Bill of Materials](https://github.com/phazil/Purple-Project-Redux/blob/main/Docs/Bill%20of%20Materials.md)
   	* [Ordering Panels and PCBs](https://github.com/phazil/Purple-Project-Redux/blob/main/Docs/Ordering%20Guide.md)
 	* [Printing Parts](https://github.com/phazil/Purple-Project-Redux/blob/main/Docs/Printing%20Parts.md)
	* [Rough Assembly Guide](https://github.com/phazil/Purple-Project-Redux/blob/main/Docs/Assembly%20Guide.md)
 	* [Editting Parts](https://github.com/phazil/Purple-Project-Redux/blob/main/Docs/Editting%20Parts.md)

## Features, Details, and To-Dos

3 Variations:
- Purple Project Redux: 35.56cm x 20.32cm x 2.32cm (14" x 8" x 0.9")
- **UNTESTED** Acrylic Layer Version: 35.56cm x 20.32cm x 2.47cm (14" x 8" x 0.97")
- Right side carrying handle modifcation available for both (Adds about 1.25" to total length)

Features:
- Daigo-ish Layout
- Stickless+
- Bottom Rubber Pads
	- Mirrored for both sides
- Right side carrying handle
- PCB top/bottom plate (1.6mm)
- Possible Acrylic Top Plate (3.1mm total thickness, only screw ins work)
- Designed PCB Auxilliary Button Panel

Each designed part can fit in a 250x250x250 volume print bed
- 6 total pieces
	- Top Left
	- Top Right
	- Top Middle (Requires USB-C keystone jack panel mount)
	- Bottom Left
	- Bottom Middle
	- Bottom Right
- Printed in [Voron Spec](https://docs.vorondesign.com/sourcing.html#print-settings) hopefully

To Do's:
- ~~BOM Page written~~
- Ordering Page written
- ~~Printing Parts written~~
- Rough Assembly Guide written
- ~~Editting Parts written~~
- Bottom Rubber/Foam pad DXFs
