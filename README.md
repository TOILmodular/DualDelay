# Dual Delay - PT2399 Dual Delay Effect Eurorack Module
Simple analog Eurorack dual delay module based on the Dreadbox White Line Echo module.

<img height="500" src="https://github.com/TOILmodular/DualDelay/assets/97026614/136cae8c-ddec-4335-830b-79532fee6b81"><img height="500" src="https://github.com/TOILmodular/DualDelay/assets/97026614/4f1385d1-0660-45fc-9a27-415d6ebd3a91">

<img height="500" src="https://github.com/TOILmodular/DualDelay/assets/97026614/03924c09-adc2-4ae8-ba09-daa15417bfbd"><img height="500" src="https://github.com/TOILmodular/DualDelay/assets/97026614/35404820-8cef-4415-9d73-bc863c32f00c">

## Module Build and PCBs
In the folder GerberFiles, I added two different versions for the control board, an "original" and a "Thonk" version.
Reason is that for my own module, I am using specific potentiometers - 16K4 series from Supertech Electronics - and 3.5mm jack sockets - MJ-355 from Marushin - available for me at a local electronics shop.

<img height="500" alt="CtrlPCB_Orig" src="https://github.com/TOILmodular/DualDelay/assets/97026614/e64031df-df01-4a12-b13b-4da1d343ca02">

However, since most DIY projects for Eurorack modules out there are using potentiometers from ALPHA and so-called THONKICONN jacks, as they are provided by Thonk in the UK, I also created another control board PCB version, called "Thonk", with footprints for those components.

<img height="500" alt="CtrlPCB_Thonk" src="https://github.com/TOILmodular/DualDelay/assets/97026614/86ac9655-e957-4ebb-95cb-32501b49af47">

The main board PCB is the same for both versions.

<img height="500" alt="MainPCB" src="https://github.com/TOILmodular/DualDelay/assets/97026614/6b92d4f4-1f3b-4801-8070-6e9368c4179f">

I created the Gerber files with the online tool EasyEDA and ordered it at JLCPCB.

## Panel Layout
I added the information about hole coordinates for the front panel in the folder PanelLayout, referring to the component layout in the Gerber files. The layout is the same for all PCB versions.

In addition, there is a Gerber file for the panel, following the HP standard. My own modules do not follow that width standard, as I am only using sliding nuts in my racks.

You can use the panel Gerber file to have the panel built out of PCB material.

## Additional Information about Components
The module design is mainly through-hole with the exception of several SMD capacitors (package 1608 metric or 0603 imperial) and two PNP transistors (package SOT-23).

Concerning the resistor size, I am usually using small-size resistors, about half the length of the usual size, so they need less space on the PCB. If you want to use my Gerber files, you have to consider that fact. You might still use normal size resistors and put them in a standing position on the boards. Should also work fine.

On the control board, you will find electrolytic capacitors with a rectangle next to them. Since these capacitors are too tall for standing upright on the board with the main board on top of it, those capacitors need to be mounted in a rectangular position. The rectangle shows the position for each bent-over capacitor.

<img height="300" src="https://github.com/TOILmodular/DualDelay/assets/97026614/46a7719f-bb04-439e-8b7f-10059506cbe2">
