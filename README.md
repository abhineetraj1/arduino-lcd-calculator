# Arduino hand calculator
Arduino Calculator made in C with Arduino IDE

## Requirements
* Arduino UNO board
* Liquid crystal display 16x2
* Arduino keypad (4x4)

## Wire connections

*  uno:GND.1 : lcd:VSS
*  uno:GND.1 : lcd:K
*  uno:GND.1 : lcd:RW
*  uno:5V : lcd:VDD
*  uno:5V : r1:2
*  r1:1 : lcd:A
*  uno:12 : lcd:RS
*  uno:11 : lcd:E
*  uno:10 : lcd:D4
*  uno:9 : lcd:D5
*  uno:8 : lcd:D6
*  uno:7 : lcd:D7
*  uno:A3 : keypad:C1
*  uno:A2 : keypad:C2
*  uno:A1 : keypad:C3
*  uno:A0 : keypad:C4
*  uno:5 : keypad:R1
*  uno:4 : keypad:R2
*  uno:3 : keypad:R3
*  uno:2 : keypad:R4

# Installation
* Download Arduino IDE.
* Open main.ino file and upload the code into arduino board.
* Attach all the wires, according to above info/
* Run your Arduino :)

# Programming languages used:-
<a href="https://docs.microsoft.com/en-us/cpp/?view=msvc-170" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/c-colored.svg" width="36" height="36" alt="C" /></a><a href="https://www.arduino.cc/" target="_blank" rel="noreferrer"> <img src="https://cdn.worldvectorlogo.com/logos/arduino-1.svg" alt="arduino" width="40" height="40"/> </a>