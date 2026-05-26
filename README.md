# week-3-hardware-resolution
# NE555 LED Blinker

I'm building a 555 timer LED blinker because I wanted to learn 
how ICs work and design my own PCB around one.

## May 26 - Schematic Design

I designed the schematic for my 555 LED blinker in KiCad.
The circuit i made used a NE555P timer in astable mode to blink an LED
on and off automatically with The timing being controlled by resistors and a capacitor
I ran into some issues figuring out how to wire the 555 correctly
but eventually got it working with no ERC violations and here is the schematics 
<img width="729" height="587" alt="Screenshot 2026-05-26 at 4 33 16 PM" src="https://github.com/user-attachments/assets/54660bb0-7a60-4c18-9571-fc082a15a39a" />

 I  routed the PCB i placed all the components down and rounded the
corners on the board outline to make it look cleaner.
the pcb 
<img width="567" height="397" alt="Screenshot 2026-05-26 at 4 33 31 PM" src="https://github.com/user-attachments/assets/d8c9d287-69c6-4795-8fd7-0ee781953410" />
pcb render 
<img width="654" height="529" alt="Screenshot 2026-05-26 at 4 33 51 PM" src="https://github.com/user-attachments/assets/c2fed8b7-3090-474e-b09f-446dc0242951" />

The DRC passed with no errors.

### Time Spent: 1 Hours
