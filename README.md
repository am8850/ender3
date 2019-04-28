# My adventures in 3D printing

I recently bought an Ender 3 (not the pro). I wanted to share my experiences thus far.

## Build

I mostly followed the following guide to build my printer:

https://www.youtube.com/watch?v=me8Qrwh907Q

I think the author makes very good recommendations as part as aligning the printer. I did not change all the parts he recommends, and so far my printer has been working ok. I do plan to upgrade the parts in the near future.

## Leveing and distance from the nozzle to the bed.

> **Note:** Do not attempt to print until the bed is level and you have set the proper height between the nozzle and the printing surface. Otherwise, you could scratch and ruing the printing surface.

Bed leveling and distance from the nozzle to the bed are probably the most important aspects of 3D printing. 

Once my printer was built. I had the printer Auto Home from the prepare setting in the LCD. This puts the nozzle outside the printing area. Then I turned off the printer and moved the nozzle to front left corner. I knew that my z-stop switch was install correctly because there was enough distance between the nozzle and the printing bed. Had I forced the nozzle to this position without a proper z-stop positon, I could have scratched the printing surface and the bed. Fortunately, this did not happen. I then proceeed to level the back right corner, the to right corner, and the back left corners.

I originially used a business card to level the nozzle to the printing surface, but after a couple of prints, this was not working. I contacted a friend and he told me to use instead a non-folded sheet of paper to try to achieve a .1mm thickness. This works by putting the paper under the nozzle and bringing to a position where there's drag between the paper, nozzle and printing surface. After I leveled the bud using the paper, I was succesful in printing my first few prints. 

Leveling took a long time for me, and every time I printed something it seemed that I needed to readjust the leveling. I searched online for a faster way to do the leveling and fount the following video:

https://www.youtube.com/watch?v=_EfWVUJjBdA

The video also has a link to a Thingverse link for the gcode files the presenter mentions in the video:

https://www.thingiverse.com/thing:3235018

By using this gcode file, I have been able to set my bed leveling consistently and faster.

## Printing temperature (PLA)

I have printed PLA both at 210C nozzle temperature and 65C bed temperature and at 200C nozzle temperature and 60C bed temperature. I had good results with both. Lately, I have been keeping the latter setting as it is the one that comes with Cura by default.

## My first and the benchy test

My first successful print was a 20x20mm square.

[Inser Image]

This is what my benchy looks like.

## Additional parts

Once I overcame the leveling and nozzle distance issues and after several failed and then successfult prints, I then decided the print the following parts to enhace my printer:

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

I finally settle for using Cura.


## Design software

I am still using tinkercad to do my design. I also have started looking a FreeCad.

## Printing duplicates

Sometimes you may want to print several duplicates of your parts. Rather than printing one by one, I either import the STL file into tinkercad and created duplicates or import the same STL file into Cura several times. I like the second approach, as I can go into inmidiatly go into slicking, Additing the files via Tinkercad though, gives a lot of flexibility.


## Other Issues

### Stuck items

- Be patient. Let the bed cool down to room termpature, and remove the item(s) with the spula. You could also desigh your prints with a tiny edge corner to be able to have spatula catch better and faster.
- Clean the printing surface after every print.

### Stringing

Stringing occurs when the nozzle moves from one location to another rapidly, particularly after making circle, leaving in its path a small amount of filament that looks like a string. This can be prevented using the Combing Mode in Travel setting in Cura.
