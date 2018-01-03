Raspberry Pi USB Extension
==========================

(C) 2018 John C Kha

[Hosted on Github](https://github.com/sirkha/RPiUSBExt)

CC-BY-SA 4.0 - See License.text for more details

Purpose and Use
---------------
This board set provides two PCBs that plug into the USB ports on a Raspberry Pi and 
a board that connects to them via an RJ45 connection. Provisions for LEDs are
provided.

### TLDR ###
Solder an ethernet cable (CAT 5, CAT 5e, CAT 6) to the two smaller boards and
terminate the other end with an RJ45 connector. Provide power to the larger
board and plug in the ethernet cable. Plug the two smaller boards into your Pi.

### BOM ###
Links are examples, not endorsements.


 -  2 x [Dual USB Recepticals][BOM01]
        I don't know that this is actually standardized, but the different ones I
        found sure seem similar.
 -  1 x [RJ45 Receptical][BOM02]
        Also fairly standardized, though less so. Get the small ones and make sure
        the LED pins are in the back
 -  1 x [2x3 header with 2.54 mm spacing][BOM03]
 -  1 x [RJ45 Jack][BOM04]
 -  1 x [CAT5/5e/6 cable][BOM05]

Wire for connecting the LEDs and power is not included in the BOM. 20 AWG is
recommended for power to prevent excessive voltage drop. Consider providing
power seperately to the USB devices.

[BOM01]:https://www.digikey.com/product-detail/en/omron-electronics-inc-emc-div/XM7A-0442A/OR1070-ND/2755612
[BOM02]:https://www.digikey.com/product-detail/en/amphenol-commercial-products/RJHSE-5481/RJHSE-5481-ND/1242705
[BOM03]:https://www.sparkfun.com/products/10877
[BOM04]:https://www.amazon.com/CableWholesale-Crimp-Connector-Pieces-31D0-500HD/dp/B000I21YDM/
[BOM05]:https://www.amazon.com/Cat5e-1000ft-Ethernet-Cable-White/dp/B004PL082U

### Detailed Description ###

TODO: Write a detailed description

### Assembly Instructions ###

TODO

### Instructions for Use ###

TODO

Thanks
------
This project was inspired by and draws from work by 
[Dustin Westaby](http://www.westaby.net/2017/01/mini-nes-build-w-functioning-cartridge-loader/).
