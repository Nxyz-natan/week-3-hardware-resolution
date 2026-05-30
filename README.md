# week-3-hardware-resolution
# NE555 LED Blinker

A PCB that uses a NE555P timer IC in astable mode to automatically 
blink an LED on and off The timing is controlled by resistors and 
a capacitor connected to the 555 timer

PCB Render
<img width="732" height="450" alt="Screenshot 2026-05-29 at 6 55 55 PM" src="https://github.com/user-attachments/assets/5d6079d5-fb3a-4a78-aba4-3bb5a85d6671" />

## How it works

The NE555P runs in astable mode generating a continuous square wave 
signal The frequency is determined by R4 (10k) R5 (1k), and C1 (10uF) 
A 470Ω resistor (R6) limits current to the LED to prevent it from burning out

KiCanvas Link: https://kicanvas.org/?repo=https%3A%2F%2Fgithub.com%2FNxyz-natan%2Fweek-3-hardware-resolution%2Ftree%2Fmain%2Fsrc



## Schematic

Schematic: <img width="830" height="563" alt="Screenshot 2026-05-29 at 6 57 49 PM" src="https://github.com/user-attachments/assets/a26e4e48-3a00-498f-8fba-46ea84f8be15" />


## PCB

PCB: <img width="936" height="600" alt="Screenshot 2026-05-29 at 6 57 31 PM" src="https://github.com/user-attachments/assets/7804812e-24bd-455b-a53b-36862f725b8a" />
