# My adventures in 3D printing

I recently bought an Ender 3 (not the pro). I wanted to share my experiences thus far.

## Build

I mostly followed this guide to build my printer:

https://www.youtube.com/watch?v=me8Qrwh907Q

I think the author makes very good recommendations to align printer. I did not change all the parts as he recommended. So far, my printer has been working correctly, but I do plan to add the recommended parts in the near future.

## Leveling and distance from the nozzle to the bed.

> **Note:** Do not attempt to print until the bed is leveled and you have set the proper height between the nozzle and the printing surface. Otherwise, you could scratch and ruing the printing surface.

Proper bed leveling, distance from the nozzle to the bed (particularly the first layer), and proper material flow (by adjusting to the proper temperature) are probable the two most important aspects of 3D printing. 

Once my printer was built, I had the printer Auto Home from the prepare setting in the LCD. This puts the nozzle outside the printing area. Then I turned off the printer and moved the nozzle to front left corner. I knew that my z-stop switch was install correctly because there was enough distance between the nozzle and the printing bed. Had I forced the nozzle to this position without a proper z-stop positon, I could have scratched the printing surface and the bed. Fortunately, this did not happen. I then proceeed to level the back right corner, the to right corner, and the back left corners.

I originially used a business card to level the nozzle to the printing surface, but after a couple of prints, this was not working. I contacted a friend and he told me to use instead a non-folded sheet of paper to try to achieve a .1mm thickness. This works by putting the paper under the nozzle and bringing the bed to a position where there's drag between the paper and the nozzle. You have to do this around all corners, making sure to go on an X pattern. Then you need to move the nozzle to the center of the bed and adjust all four corners "at the same time". After I leveled the bed using the paper, I was succesful in printing my first few prints. 

Proper leveling took a long time for me. It seem that everytime I printed something, I need to re-adjust the leveling. I searched online for a faster way to level the bed and found this video:

https://www.youtube.com/watch?v=_EfWVUJjBdA

The video also has a link to a thingiverse.com to download the gcode files. The link is a follows:

https://www.thingiverse.com/thing:3235018

By using leveling and test gcode files, I have been able to set my bed leveling consistently and faster.

## Printing temperature (PLA)

I have printed PLA both at 210C nozzle temperature and 65C bed temperature and at 200C nozzle temperature and 60C bed temperature. I had good results with both. I've learned that different PLAs require different temperatures. Recently I got PLA, and I had to raise the temperature to 225C. 

| Setting | Area | Temperature |
| --- | --- | --- |
| PLA setting 1 | Extruder | 200C
|     | Bed | 60C
| PLA setting 2 | Extruder | 210C
|     | Bed | 65C
| DIKALE PLA | Extruder | 225C
|     | Bed | 60C



> Note: bottom line, test the optimal temperature of the material. I think this is achieved when you raise the temperature, extrude material and it comes flows easily in a straight line. If the material curls or you see that the extruder motor skips or makes weird noises, the temperature may be too low or there may be a blockage in the extruder. If you have the temperature set too high, it will also be a problem. Once you get a good flow, reduce the temperature until as long as you still achieve good results (material flowing in a straight line and the extruder motor is able to handle the flow).

## My first and the benchy test

My first successful print was a 20x20mm square:

[Insert image]

This is what my benchy looks like:

[Insert image|

## Additional parts

Once I overcame leveling, nozzle distance, and material extrussion issues and after several failed and then successfult prints, I then decided the print the following parts to enhace my printer:

### Fan cover

On the Ender 3 (not the pro), this prevents from particles falling into the cooling fan of the motherboard. I chose this fan cover because it has reminder arrows of how to move the bed up (clockwise) and down (anti clockwise).

https://www.thingiverse.com/thing:3505548

### Filament guide

https://www.thingiverse.com/thing:2917932

### LCD back cover


### LCD cable clips

https://www.thingiverse.com/thing:3089470

### Drag Chain

https://www.thingiverse.com/thing:2920060

## Slicing software

I finally settled for using Cura to do my slicing. I have also learned to modified the gcode and have the printer perform custom commands to for example change filament color.

## Design software

I am still using tinkercad to do my designs. I also have started looking a FreeCad.

## Printing duplicates

Sometimes you may want to print several duplicates of your parts. Rather than printing one by one, import the STL into Cura and use the duplication command to create duplicates.

## Multi-color printing

It is possible to print multiple colors with one extruder. Cura 4.0 has a nice gcode routing that makes the process very easy. You go to Setting/GCode Setting and add a routing to change filamente at a given layer number.

## Other Issues

### Stuck items

- Be patient. Let the bed cool down to room termpature, and remove the item(s) with the spula. You could also desigh your prints with a tiny edge corner to be able to have spatula catch better and faster.
- Clean the printing surface after every print.

### Stringing

Stringing occurs when the nozzle moves from one location to another rapidly, particularly after making circle, leaving in its path a small amount of filament that looks like a string. This can be prevented using the Combing Mode in Travel the settings in Cura. Having the temperature two hot also affects stringing. Make sure to have the proper temperature.

### Nozzle Clogging

I recently upgraded the boden tube to  a Capricorn one. I did not close the gap between the tube and the nozzle, as a result a clog formed. I had to unisntall the nozzle and the boden tube holder, clean the clog, and then reinstall the whole thing again without leaving a gap. This worked great and now the printer is better than ever.
