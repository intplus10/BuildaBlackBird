# BuildaBlackBird
How to build a BlackBird toolhead for Voron Trident.
It is not simple and yet it is. Only four screw holding it together.
2. Files from CAD:
https://github.com/Armchair-Heavy-Industries/Archetype/tree/main/CAD

That is what we need. The CAD contains all version, so you need to filter out every nonessential parts. The probe parts were completly out of position for me dont let it confuse you. For short hotends use the short version from EVERYTHING, for longer ones use the medium!
Check the clearences in the CAD before printing.

3. Customizations:
a, Do not use the files from source 1 and 2 mixed! I did it and I was in a trouble during assembly.
For example:
CAD_diff1 I was printed out half of the stuff, then I discovered the CAD. From that point I was sending the files directly to my slicer from Fusion360. It was a mistake. The downloaded package does not fit with the CAD data currently (2024.08.20). As I see the Configurator has the more printable version tho.

b, Better extrudermount for G2SA, and getting rid of the M3 square nuts
The original design would secure the whole assemby by M3 square nuts. Never ever I have seen one in use. I did not find on in the whole factory I work. I can see the design choice behind it (self alligning during assy), but the regular heat insert is more accessible. However that one would not self allign, and if you pressed it in a wrong angle your screw wont catch the thread. I had the same issue so I inserted the screw as much as I could, and heated up the insert again. The screw pulled it into the right position.
Lets talk about the modded design:
https://www.printables.com/model/879269-archetype-flat-orbiter-mount/files
CAD_diff2
The modded fits perfectly the G2SA stock version. The original Sherpa flat version fits perfectly the G2SA's Sherpa version I mentioned before. Watch out for the mounting hole distances! The BreakNeck is not compatible with EBB36 as I tried.

Other improvement is that this modded design has a heatinsert slot for the CAN-board mount. Lovely.

I also added an "improvement". I expanded the area where the cables are coming out in my build. You Can find it in the CAD.

CAD_diff3

c, Space for RGB cable in the face panel:
I was not able to insert the 3 wire first without ripping the soldering. So I added some space on one side. Sidenote: I only use 2 LED. The top one is kind of pointless I think. All function can be represented with the worklamps. CAD_diff4

d, X endstop mod:
As I do not want any addedd weight to my toolhead (and more wires😅) I left my XY endstop block as it was (Stock Trident). Why touch it while its working?
The toolhead does not reach the endstop switch so I added a heat insert hole to the Klicky probe mount. You can insert there a screw and adjust it as you need.
Use nuts to fixing its position!

CAD_diff5

e, Custom EBB36 mounting plate:
I tried 2 mountings for the EBB36, one did not fit, and other one also did not fit.
https://www.printables.com/model/879269-archetype-flat-orbiter-mount/files this is the same mod used for the extruder mount. Somehow the EBB36 mount did not allign well regarding the support screw. I think the Orbiter's, and the G2SA's motor placement are different so there is a shift in hole positions.
The other one was mirrored and all the holes did not lined up.
At this point I decided to design my own. TBH I just eyeballed a lot of measurement, because only imported STL was available as a reference geometry (designers, pls upload STEP also ❤️❤️). I added a place for a little 2510 fan to cool the board. Not entirely neccessary to install.

CAD_diff6

 Add a custom footer
Pages 6
Find a page…
Home
0. The configuration I have
1. Model Files and Customizations
1. Files from the original source:
2. Files from CAD:
3. Customizations:
a, Do not use the files from source 1 and 2 mixed! I did it and I was in a trouble during assembly.
b, Better extrudermount for G2SA, and getting rid of the M3 square nuts
c, Space for RGB cable in the face panel:
d, X endstop mod:
e, Custom EBB36 mounting plate:
2. Printing
3. Sourcing and deviations
Table of Content
 Add a custom sidebar
Clone this wiki locally
