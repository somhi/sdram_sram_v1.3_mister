# sdram_sram_v1.3_mister

This repository contains the schematic, altium project, gerber files and datasheets for the MiSTer dual memory module v1.3 SDRAM 32 MB + SRAM 2 MB.

This module is being used with [DECA retro cape 2](https://github.com/somhi/DECA_retro_cape_2). 

MiSTer Memtest core gives 120/130 MHz score for this module with both memories soldered. With only SDRAM soldered it gives 150 MHz.

Original project is from Sorgelig and can be found on [MiSTer-devel/Hardware_MiSTer](https://github.com/MiSTer-devel/Hardware_MiSTer) repository.

Readme from Hardware_MiSTer contain more information. Also [here](README_sorgelig.md) there is a copy.

Main components:

* SDRAM 32 MB: Winbond  W9825G6KH-6
* SRAM 2 MB: ISSI IS61WV20488FBLL-10TLI   (this is the new part number)

![SRAM_change](/home/jordi/Coding/Github/sdram_sram_v1.3_mister/datasheets/SRAM_change.png)



CKE signal enables SDRAM with 1 and SRAM with 0.



![sdram](/home/jordi/Coding/Github/sdram_sram_v1.3_mister/sdram.jpg)

![sram](/home/jordi/Coding/Github/sdram_sram_v1.3_mister/sram.jpg)