# Project  MK-968VL 
An (old) project for 486 platform: Video card based S3 Vision 968 VLB with 4MB VRAM.
It is just a Replica of the SPEA Mercury P64V PCI, in which their PCI interface was replaced by a VLB interface.
It is my first project with KiCad, it may sometimes look not so good and weird.

[Full development history at Vogons](https://www.vogons.org/viewtopic.php?f=63&t=76602)

![pictures](https://github.com/matt1187/968VL/blob/main/picture/968VL_1.jpg)




# Features
- S3 Vision968 video chipset, one of fastest Windows accelerator for the 486 VESA local bus platform
- 4 MB VRAM
- 175/220 MHz high quality RAMDAC
- Mostly rock solid 50 MHz bus clock with zero wait states
- Win 3.1 and Win 9x driver available

  
# Issues
- DDC interface is not working, fixing in future is not planned, sorry.
- heavy to find a S3 Vision968 (86C968) chip
- Card would work with a S3 Vision964 (86C964) too, but that would need modification of VGA-ROM (difference in registers) so that text/CGA/MDA modes work correctly
- Some (many) TVP3026 DAC has issuses with VESA 4bit Mode: Line Jitter  (my original SPEA Mercury P64V PCI has also line jitter) Side notice: I have two 968VL with good 4bit VESA mode
 



# Bill of Materials
- [**please read file "note_MK_968VL_002.txt"**](https://github.com/matt1187/968VL/blob/main/gerber/note_MK_968VL_002.txt)
- [config resistor picture](https://github.com/matt1187/968VL/blob/main/gerber/config_resistor.JPG)
- [bom csv file](https://github.com/matt1187/968VL/blob/main/gerber/968.csv)
- [gerber files](https://github.com/matt1187/968VL/blob/main/gerber/)
- [drawing of slot bracket](https://github.com/matt1187/968VL/blob/main/mechanical/bracket_968VL_01.pdf)

# Drivers & ROM
- [ROM dump](https://github.com/matt1187/968VL/blob/main/rom/968V_ROM.zip)
- [Windows 9x driver](https://github.com/matt1187/968VL/blob/main/driver/W95_S3_driver%200109B.ZIP)
- [Windows 3.1 driver](https://github.com/matt1187/968VL/blob/main/driver/WIN31_vision96815B4.ZIP)





# PCB Revision History
- 000 initial draft
- 001 major bug fixing (swapped inner layer, few wrong connections on ICs)
- 002 minor bug fixing (wrong footprint)
- 003 new revision moved VGA port (keystone 9200-1 istead special)) and corrected ISA slot position (12.7mm instead 13 mm  to VLB )

# License
The project is free for non-commercial reproduction. Do not sell it on Ebay or other platforms for profit. Do not make a closed source derivative. Share your experiences and ideas with the community.

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png

