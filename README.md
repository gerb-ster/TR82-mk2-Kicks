# TR82 mk2 'Kicks'

Second version of the TR82 project; proper PCB's this time! I've combined the BassDrums and the SnareDrum to 
a single board. I've added a OpAmp buffer to the output and changed the output impedance to a more standard
1k. Next to that I've also added a Gate-to-Trigger circuit based on a design by Ken Stone. It converts the 
rising edge of a Gate signal into a short trigger pulse. By changin the level of the gate/trigger input you
can control how 'hard' you hit the drums. Higher levels means more 'accent'.

The Designs and Mods of the drum voices are the same as in the 'original' TR82.

There is a 'internal trigger' connection added to the mainboarb of the PCB. This can be used to hook it up to
a seperate controller board. Maybe :). 

### Links

https://www.gerbster.nl/tr82/
https://www.elby-designs.com/webtek/cgs/cgs24/cgs24_gatetotrigger.html

## Status: Work in Progress

- done: first schematic & board design
- done: breadboard and test
- done: design frontpanel
- todo: order PCB and build prototype