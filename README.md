# mein_zoo

Market name - Zycoo U20 V2
DevTree Board Name - Olimex A20-Olinuxino Micro


Zycoo devs did not migrate from FEX allwinner format to Device Tree,
and there is old Uboot

U-Boot 2014.04-10733-gea1ac32-dirty (May 12 2015 - 03:40:53) Allwinner Technology          
                                                                                           
CPU:   Allwinner A20 (SUN7I)                                                               
===========sys ver1.0 by qz @2015.05.12================                                    
Board: A20-OLinuXino_MICRO                                                                 
I2C:   ready                                                                               
DRAM:  512 MiB                                                                             
MMC:   SUNXI SD/MMC: 0
Out:   serial                                                                              
Err:   serial                                                                              
Net:   emac

But Olimex team provides generic Armbian for their board
https://www.olimex.com/wiki/A20-OLinuXino-MICRO

Direct Link
ftp://staging.olimex.com/Allwinner_Images/A20-OLinuXino/1.latest_mainline_images/buster/images/

The board is booting to Uboot with this image


