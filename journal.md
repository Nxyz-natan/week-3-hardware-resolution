# NE555 LED Blinker

[Preface] I'm building a 555 timer LED blinker because I wanted to 
learn how ICs work and design my own PCB around one

## May 26 - Schematic Design

Today I worked on the schematic in KiCad using a NE555P timer in 
astable mode

I started by reading the 555 timer datasheet to understand how astable 
mode works and what external components I needed The timing is set by 
two resistors and a capacitor I used an online RC calculator to find 
values that give the values

I ran into trouble figuring out how to correctly wire all 8 pins of the 
555 Pins like CONT RST and DISCH weren't obvious at first I looked 
up reference schematics and cross-checked with the datasheet pin 
functions until I got it right with no ERC violations

 I routed the PCB and finished the board design

I placed all components keeping the resistors and capacitors close to 
the 555 IC to minimize trace lengths I rounded the corners of the board 
outline using the fillet tool to give it a cleaner look and filled my board with gnd net The DRC passed 
with no errors

### Time Spent: 1 Hour
