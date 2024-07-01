# Function-generator
 The circuit can generate different signals like sine and square wave with wide band of frequencies.

It is based on **ICL8038 Precision Waveform Generator/Voltage Controlled Oscillator**.

The supply voltage for this circuit is a single Li-ion Battery with a protection circuit attached, and there is charging terminal on the PCB.

The **ICL7660S voltage converter IC** was not available, so we used the **MT3608 Boost Converter** in **SEPIC inverting** methodology to supply +9 and -9 volts.

Another MT3608 was used as a normal **step-up** circuit to supply the main voltage of 12 volts. 

The design inspired by a Chinese kit with following schematic:

![](https://github.com/AhmedHafez2000/Function-generator/blob/main/Schematic/ICL8038-function-generator-kit.JPG?raw=true)
![](https://github.com/AhmedHafez2000/Function-generator/blob/main/Photos/Kit.jpg?raw=true)

This circuit can be fabricated in home a printable file is attached in PCB folder.

## DIY Sample
![](https://github.com/AhmedHafez2000/Function-generator/blob/main/Photos/IMG_1.jpg?raw=true)
![](https://github.com/AhmedHafez2000/Function-generator/blob/main/Photos/IMG_2.jpg?raw=true)

The printer quality was poor so that the acid came through the ink and etched unwanted area :sweat_smile:, but it was fixed and circuit works perfectly.

## Schematic
![Schematic](https://github.com/AhmedHafez2000/Function-generator/blob/main/Schematic/Function_generator-Sch.png?raw=true)

## 2D PCB
![2D PCB](https://github.com/AhmedHafez2000/Function-generator/blob/main/PCB/2D-Top.png?raw=true)
![2D PCB](https://github.com/AhmedHafez2000/Function-generator/blob/main/PCB/2D-Bot.png?raw=true)
**NOTE:** The top connection are jumper wires.

## 3D PCB
![3D PCB](https://github.com/AhmedHafez2000/Function-generator/blob/main/PCB/3D-Top.png?raw=true)
![2D PCB](https://github.com/AhmedHafez2000/Function-generator/blob/main/PCB/3D-Bot.png?raw=true)