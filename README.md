# recurBOY

__recurBOY__ is a raspberry pi zero based diy video-instrument for live performance.

![alt text](img/recurboy-horizontal.jpg "recurBoy")

### motivation

it was designed to be built together with others in group workshop sessions.

for many people there is a barrier to enter the world of hardware video-art making instruments - both due to the general higher cost of video gear compared with audio equipment and in some cases its obsolescence and thus rarity.

this project aims to remove these financial barriers while enabling anyone interested to build their own art-making tools. by creating together we can learn from each other and help foster community in a physical space.

### features

- outputs composite video
- 2 source modes : _sampler_ and _shaders_
- process any source with additional _FX_
- control shader/fx parameters directly with 4x knobs or externally with 4x cv inputs

![alt text](img/background.png "recurBoy")

## BOM

REF | NAME | NUMBER | REF | APROX COST (euro)
--- | --- | --- | --- | ---
na | [raspberry pi zero] | 1 | NA | 5, 12 - 18
na | custom pcb 100x100mm | 1 | NA | 5
J5 | [1.8" screen] | 1 | NA | 4
SW1-5 | [push buttons + caps] | 5 | NA | 1 
RV1-4 | 10k linear pots | 4 | PTV09A-4025UB103 (mouser) | 3
J1-4 | [thonkicon jack] inputs | 4 | A-2563  | 2
U1 | [mcp3008 a2d dip] | 1 | A-2470 | 2
U1 | IC 16pin socket | 1 | A-003 | 0.5
R1-4 | 1k resistors | 4 | A-3772 | 0.5
D1-8 | bat46 diodes| 8 | A-1095 | 2
J8 | 2x20 pin header | 1 in 1 out | A-195 , 1/2 of A-196 | 1
J7 | [composite video jack] | 1 | 490-RCJ-024 (mouser) | 1
na | [sd card 8gb] | 1 | NA | 2 |
na | power-adapter | 1 | A-3167 (US) , A-3166 (EU) |  5
J9 | [5-way push button] | 1 | NA | 1.5

[cheaper 5-way push buttons](https://www.aliexpress.com/item/32998891073.html?spm=a2g0o.cart.0.0.7c183c00s7Cy0m&gps-id=shopcart_buyagain&scm=1007.13440.139630.0&scm_id=1007.13440.139630.0&scm-url=1007.13440.139630.0&pvid=50241eba-8280-43af-a44d-d995130093bc)

aprox total cost : 30euro plus the raspi0 - can get for 5euro from some distributors

additional parts:

- 1-pin header and socket for tv-out
- DIP8 ic socket
- usb-micro to USB-A socket to attach usb
- USB drive
- a rca cable
- a composite tv, display or mixer
- some M2 screws, nuts and spacers

[raspberry pi zero]: https://www.berrybase.de/raspberry-pi-zero-v1.3
[1.8" screen]: https://www.aliexpress.com/item/32996979276.html
[mcp3008 a2d dip]: https://www.aliexpress.com/item/32735896933.html
[push buttons + caps from china]: https://www.aliexpress.com/item/32826994795.html
[thonkicon jack]: https://modularaddict.com/pj301m12-jacks
[sd card 8gb]: https://www.aliexpress.com/item/33040093922.html

[composite video jack]: https://www.mouser.de/ProductDetail/CUI/RCJ-024
[5-way push button]: https://www.aliexpress.com/item/32845147449.html

## FAQ:

### How can you load your own video files

1. You need to create a folder called `Videos` in the root of the usb stick. 

2. This is where the usb cable goes if you are looking at the recurBoy from the front. It has to be on the right side of the raspberrypi zero. You will need the usb adapter that's part of your kit. The usb stick needs to be inserted BEFORE you turn on your recurBoy. 

![](img/usb-where.png "where to put usb")

![](img/splash.gif "Splash Screen")
