## Panel Layout for PCB

The panel dimensions provided in the section "Original Design" below are based on my own module build, since I am not following the standard HP (1HP eq. 5.08mm) size. An alternative by building an HP-standard size panel can be found in the section "HP Standard Design" further below.

### Original Design
Coordinates given in the table fit to the layout of components given in the PCBc in folder GerberFiles.
The layout is the same for both versions.

Panel size: 40mm x 128.5mm

The numbers in the table are refering to the numbers in the picture below.
Coordinates origin is the lower left corner of the panel.


| No. | X-coord. [mm] | Y-coord. [mm] | Comment |
| --- | --- | --- | --- |
| 1 | 11 | 105 | Left Delay Time Pot |
| 2 | 29 | 105 | Right Delay Time Pot |
| 3 | 11 | 82 | Left Feedback Pot |
| 4 | 29 | 82 | Right Feedback Pot |
| 5 | 11 | 59 | Left Mix Pot |
| 6 | 29 | 59 | Right Mix Pot |
| 7 | 12.5 | 38.5 | Left Delay Time CV Jack |
| 8 | 27.5 | 38.5 | Right Delay Time CV Jack |
| 9 | 12.5 | 25.75 | Left Input Jack |
| 10 | 27.5| 25.75 | Right Input Jack |
| 11 | 12.5 | 14 | Left Output Jack |
| 12 | 27.5 | 14 | Right Output Jack |

<img height="1200" src="https://github.com/TOILmodular/DualDelay/assets/97026614/798c1be0-e299-46b1-a8e5-87988a1bfcac">

### HP Standard Design

For building the panel with a size following the HP standard, you can use the panel Gerber file provided in the folder "GerberFiles".
I ordered my own panel via such gerber file built out of PCB material.

Here are a few parameters of the panel.
| Parameter | Value |
| --- | --- |
| Width | 8HP |
| Pot hole diameter | 8mm |
| Jack hole diameter | 6.1mm |
| Mounting hole diameter | 3.2mm|
