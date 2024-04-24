# Project  MK-968VL 
A (old) project for 486 platform: S3 Vision 968 VLB with 4MB VRAM.
It is just a  Replica of  SPEA Mercury P64V PCI, which their PCI interface is replaced by  VLB interface.
It is my first project with KiCad, it may sometime be not soo good and weird.

Full history ->  https://www.vogons.org/viewtopic.php?f=63&t=76602

![pictures](https://github.com/matt1187/968VL/blob/main/picture/968VL_1.jpg)




# Feartures
- S3 Vision968 video chipset, one of  fastest windows accelerator for 486 VESA local bus platform.
- 4 MB VRAM
- 175/220 MHz highquality RAMDAC
- mostly case: rock solid  50 MHz bus-clock with zero wait-state
- Win 3.1 and Win9x driver available

  
# Issuses
- DDC interface not working, no fixing in future, sorry.
- heavy find of  S3 Vision968 (86C968) chip
- Card would work with S3 Vision964 (86C964) , but it need modification of VGA-ROM (difference register ) for correct working text/CGA/MDA-mode

 



# Bill of material
- [**pleas read file " note_MK_968VL_002.txt"**](https://github.com/matt1187/968VL/blob/main/gerber/note_MK_968VL_002.txt)
- [config resistor picture](https://github.com/matt1187/968VL/blob/main/gerber/config_resistor.JPG)
- [csv file](https://github.com/matt1187/968VL/blob/main/gerber/968.csv)
- [gerber file](https://github.com/matt1187/968VL/blob/main/gerber/)
- [drawing of pc bracket](https://github.com/matt1187/968VL/blob/main/mechanical/bracket_968VL_01.pdf)

# Driver & ROM 
- [ROM dump](https://github.com/matt1187/968VL/blob/main/rom/968V_ROM.zip)
- [Windows 9x driver](https://github.com/matt1187/968VL/blob/main/driver/W95_S3_driver%200109B.ZIP)
- [Windows 3.1 driver](https://github.com/matt1187/968VL/blob/main/driver/WIN31_vision96815B4.ZIP)





# PCB Revision History
- 000 initial draft
- 001 major bug fixing (swapped innere layer, few wrong connection on ICs )
- 002 minor bug fixing (wrong footprint)


# License
The project is free for non-commercial reproduktion. Do not sell it on ebay or other platforms for profit. Do not make a closed source. Share your experiences and ideas with the community.
CC NC BY SA

