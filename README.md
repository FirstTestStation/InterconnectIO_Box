# FIRST STATION TEST InterconnectIO_BOX 500-1000-010


## Project Overview
This project involves the assembly of a custom **InterconnectIO_BOX** designed to be part of the **First Test Station** project ([FTS](https://dlock8.github.io/FTS_Website/)). The primary goal of the InterconnectIO_BOX is to provide an interface between instruments and the Unit Under Test (U.U.T).

![Box](DOC/Image/InterconnectIO_Box_complete.jpg)


### Design Tools
- [Freecad 0.20.2 ](https://www.freecad.org/) - Free software application used to design rail guides and assemble the box.
- [Inkscape 1.1.2 ](https://inkscape.org/) - Free software application used to design front and back panel.
- [LibreOffice](https://www.libreoffice.org/download/download-libreoffice/) - Free Software application used to create assembly instructions and the Bill of Materials (BOM).
- [PicPick](https://picpick.app/en/) - Free application to capture and document image.

### Features

- **Stand-alone Operation**: The box is capable of functioning independently, without requiring external instruments or additional equipment.
- **Rackmount Capability**: Designed to be easily mounted in a standard rack chassis, providing flexibility for different setups.
- **Cost-Effective**: Built using affordable, readily available components, ensuring low production costs.


## Assembly Instructions
   Follow the document [Assembly_Instructions](pdf/InterconnectIO_Box_Assembly_Instruction_520-1000.pdf) to complete the assembly of the board.

## Design Files
- [Left Card Guide stl File](Drawing/Left_guide_drawing_515-1000.stl) – STL file for the left rail, to be used with a 3D printer.
- [Rigth Card Guide stl File](Drawing/Right_guide_drawing_515-1010.stl) – STL file for the rigth rail, to be used with a 3D printer.
- [Front panel drawing](Drawing/Panel_Front_drawing_512-1000.svg) – SVG file for the front panel, to be used with a laser cutter.
- [Back panel drawing](Drawing/Panel_Back_drawing_512-1010.svg) – SVG file for the back panel, to be used with a laser cutter.
- [Bill of Materials(BOM)](pdf/BOM_Hardware_Assembly_InterconnectIO_Box_500-1000.pdf) – List of components required to complete the assembly.
- [Freecad Folder](Freecad/) – Freecad Original design files.


# Verification
The **InterconnectIO Box** is equipped with multiple built-in features designed to facilitate the comprehensive verification of hardware functionality. It supports **SCPI commands**, allowing for internal testing and diagnostics. The hardware has been engineered specifically to aid in the validation of board functionality, ensuring thorough and efficient testing.

For detailed testing procedures, please refer to the [Test_Instructions](pdf/InterconnectIO_Box_Test_Instruction_520-1010.pdf) document to complete the verification of the InterconnectIO Box.





