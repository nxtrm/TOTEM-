# TOTEM PCB FILES

## MANUFACTURING
If you want to get the PCB made you need to generate GERBER and Drill files in KiCAD and upload them to a manufacturer's website.
GEIST recommends [JLCPCB](https://jlcpcb.com/), [Seeed Fusion](https://www.seeedstudio.com/fusion_pcb.html) or [PCBway](https://www.pcbway.com/), and I used JLCPCB, which had the most reasonable prices for me.
If you want the silkscreen in yellow [AllPCB](https://www.allpcb.com/online_pcb_quote_new.html) is a pretty affordable choice.

- generate the gerber and dril files [TUTORIAL](https://jlcpcb.com/help/article/How-to-generate-Gerber-and-Drill-files-in-KiCad-6)
- upload the ZIP file to the website of the manufacturer.
- sometimes the Gerber preview from JLCPCB can't display the PCB, even when the files are fine. In this case use these dimensions: 258.7mm * 94.35mm
- PCB Thickness 1.6mm
- 2 layers
- PCB Qty as much as you like. One PCB is a full keyboard.
- PCB Color Black (or any other color you like)
- No impedance control
- Surface Finish HASL(with lead) if you want the easiest soldering experience or LeadFree HASL.
- Remove Order Number Yes

***

## TAKE A DEEPER LOOK OR MODIFY 

You can download the project if you need to take a deeper look or modify something. You need the Open Source software [KiCad](https://www.kicad.org/) to open it.
