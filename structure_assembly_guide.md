# Assembly Guide for Support Structures

This guide provides detailed instructions on how to assemble the Chlorophyll-Fluorometer structures.

## Prerequisites

Before starting the assembly process, ensure you have the following tools and components ready:

- Components from the [Components List](hardware/components.md)
- PVC glue
- Sandpaper
- PVC stripper
- Laser cutter
- Screws, nuts, washers, spacers
- Paper towel or rag
- Wires (red and black)
- Soldering station



## Step 1 : Assemble the LEDs and photodiode support

Start by soldering wires to the LEDs and photodiode terminal. Pay attention to the polarity of the terminals : you can solder a red wire on the + terminals of the LED and the cathode terminal of the photodiode. A black wire can be soldered on the - terminals of the LEDs and on the anode of the photodiode.

When this is done, you can assemble de following components :
- Two LEDs
- Photodiode
- (Red filter : 16 x 20 mm) X3
- 3D printed support

<p align="center">
  <img src="images/3D_printed_structure_assembly/0.components.jpg" alt="0.components" width="400"/>
</p>

1. Position the LEDs in their slots. If they don't fit, you can lightly file the LEDs bases. The LEDs must be perfectly held by the support and must not move. The wires must come out of the back of the bracket.

<p align="center">
  <img src="images/3D_printed_structure_assembly/1.LEDs.jpg" alt="1.LEDs" width="400"/>
</p>


2. Position the photodiode in its slot. Bend the wires to make them come out of the back of the bracket.

<p align="center">
  <img src="images/3D_printed_structure_assembly/2.Photodiode.jpg" alt="2.Photodiode" width="400"/>
</p>

3. Add the three pieces of red filter. You can slide them in the photodiode slot, this will hold everything in place in the holder. However, make sure that the filters are perfectly flat on the photodiode, or light could pass underneath. You can add a small piece of scotch tape to the end of the filters and fold it over the photodiode so that nothing escapes.

<p align="center">
  <img src="images/3D_printed_structure_assembly/3.Filters.jpg" alt="3.Filters" width="400"/>
</p>





## Step 2 : Assemble the internal structure

The materials required for this step are :
- The Arduino UNO R3 board
- The PCB board with all the electronic components (Screen, SD Card shield)
- 4 spacers of 5 mm
- 4 screws, diameter 3 mm, length 5 mm + nuts
- 16 spacers of 30 mm
- 4 countersunk screw, diameter 3 mm, length 8 mm + nuts + washers
- 2 screws, diameter 3 mm, length 10 mm + nuts + washers
- 2 screws, diameter 2 mm, length 12 mm + nuts + washers
- A powerbank (100 x 50 x 2.5) mm max
- A dual output power supply and angled USB output cable
- The LEDs and photodiode support made in the previous step
- Matt black PMMA sheet, thickness 3 mm
- PMMA sheet, thickness 2 mm
- Screwdriver
- Laser cutter

<p align="center">
  <img src="images/structure_assembly/0.components.jpg" alt="0.components" width="500"/>
</p>

1. Cut the structure in the PMMA sheets with the laser cutter. In 2 mm PMMA, cut the [top plate](hardware/Ready_to_laser_cut_Top-Plate.svg). In black PMMA, cut the [face and bottom plates](hardware/Ready_to_laser_cut_Structure-Plans.svg).

<p align="center">
  <img src="images/structure_assembly/1.laser_cutter.jpg" alt="1.laser_cutter" width="400"/>
</p>


2. Screw 3 screws and 5 mm spacers to the Arduino board, as shown in the photo below. Connect the PCB to the Arduino board.

<p align="center">
  <img src="images/structure_assembly/2.arduino.jpg" alt="2.arduino" width="400"/>
</p>


3. Take the face plate. Locate the side where the Arduino board goes. On the opposite side, screw the SD Card shield. Put a washer between the shield and the plate. The screws must protrude from the side of the module. You can loosen the nuts slightly, the height of the module will then be adjusted. Add a screw and a 5 mm spacer in the hole at the bottom left of the module.

<p align="center">
  <img src="images/structure_assembly/3.SD_module.jpg" alt="3.SD_module.jpg" width="300"/>
</p>


4. Screw the Arduino board on the opposite face of the plate.

<p align="center">
  <img src="images/structure_assembly/4.middle_structure.jpg" alt="4.middle_structure" width="500"/>
</p>


5. Take the bottom plate and the LEDs and photodiode support. Screw the LEDs and photodiode support under the bottom plate. Make sure that the large hole in the plate is on the same side as the wires. You can loosen the nuts for now, the position of the support will be adjusted. Pass the wires through the hole.

<p align="center">
  <img src="images/structure_assembly/5.bottom.jpg" alt="5.bottom" width="400"/>
</p>


6. Take a plug. Adjust the position of the support. It should be in the center of the plug, and so should the plate. When the positions are correct, tighten the screws.

<p align="center">
  <img src="images/structure_assembly/6.centering.jpg" alt="6.centering" width="400"/>
</p>


7. Screw the spacers into the four corners.

<p align="center">
  <img src="images/structure_assembly/7.spacers.jpg" alt="7.spacers" width="400"/>
</p>


8. Screw the LEDs and photodiode wires into terminal strips of the PCB.

<p align="center">
  <img src="images/structure_assembly/8.wires.jpg" alt="8.wires" width="400"/>
</p>


9. Put the face plate in the bottom plate, bend the wires of the LEDs and photodiode. Make sure the LEDs and photodiode didn't move in the process.

<p align="center">
  <img src="images/structure_assembly/9.center.jpg" alt="9.center" width="400"/>
</p>


10. Screw the top plate. You can now adjust the position of the SD card shield so that it can be removed easily, but without protruding too far. Tighten the screws when the position is good.

<p align="center">
  <img src="images/structure_assembly/10.top.jpg" alt="10.top" width="400"/>
</p>


11. Put the powerbank and the alimentation cable.

<p align="center">
  <img src="images/structure_assembly/11.battery.jpg" alt="11.battery" width="400"/>
</p>


## Step 3 : Assemble the waterproof box

In this step, you will need :
- PVC sleeve
- Two PVC inspection plugs
- transparent PMMA plate
- PVC glue
- Sandpaper
- PVC stripper
- Laser cutter
- Paper towel or rag
- Ø89 mm and Ø84 mm hole saws
- Angle grinder

<p align="center">
  <img src="images/box_assembly/0.components.jpg" alt="0.components" width="400"/>
</p>

1.  Cut out the inside of the plugs, one with the 89 mm in diameter hole saw, and the other with the 84 mm in diameter hole saw. Make sure the holes are at the center of the plugs. Using a laser cutter, cut two PMMA discs, one 96.5 mm in diameter, the other 82.5 mm in diameter. The disc of 82.5 mm diameter needs to be sanded to fit perfectly in the plug. Using an angle grinder, sand one edge of the disc.

<p align="center">
  <img src="images/box_assembly/1.plugs.jpg" alt="1.plugs" width="400"/>
</p>

2.  Glue the PMMA discs to the plugs : the smallest disc goes into the plug with the smallest hole, on the outside. The largest disc goes into the plug with the largest hole, on the inside of the plug. To glue, start by sanding the surfaces to be glued, then clean them with paint stripper. Apply a generous amount of glue to each surface, and press the pieces together firmly. Leave to dry for at least an hour. Then you can test the watertightness of the adhesive by placing the plugs on the surface of the water. If they float and there is no seepage, the bond is correct.

<p align="center">
  <img src="images/box_assembly/2.glued_plugs.jpg" alt="2.glued_plugs" width="300"/>
</p>


3. Glue the rings for screwing on plugs to the sleeve. As above, sand the surfaces to be glued, then clean them. Apply a generous amount of glue. Leave to dry for at least an hour. You can test for leaks on either side by screwing on the plug with the smallest window and dipping the sleeve halfway into the water. If there is no infiltration, the bond is correct.

<p align="center">
  <img src="images/box_assembly/3.sleeve.jpg" alt="3.sleeve" width="400"/>
</p>

4. Glue the plug with the largest window to one side of the sleeve. Apply a generous amount of glue to the threads of the sleeve and plug. Also apply glue to the gap between the sleeve and the plug, on the outside of the sleeve and on the indside, between the PMMA disc and the sleeve. Leave to dry for several hours. Test for leaks by immersing the sleeve halfway in water. If there are any leaks, add glue to the inside and/or outside of the sleeve where the leaks are. Allow to dry again and try again. You may need to repeat the operation several times until the seal is perfect.

<p align="center">
  <img src="images/box_assembly/4.bottom.jpg" alt="4.bottom" width="400"/>
</p>

The box is waterproof. The glued plug is the bottom, where LEDs and photodiode are located. The removable plug is on the top. Make sure that the seal is still present in the top cap when you close it, overwhise it may not be waterproof.


## Step 4 : Assemble the fluorometer

Slide the internal structure into the box. It must be at the bottom and must not move. Switch on the battery, and close the box.

<p align="center">
  <img src="images/Final_prototype.jpg" alt="Final_prototype" width="400"/>
</p>
<p align="center">
  <img src="images/Final_prototype2.jpg" alt="Final_prototype2" width="400"/>
</p>
