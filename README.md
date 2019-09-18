## Adafruit Hallowing M4 PCB

<a href="http://www.adafruit.com/products/4300"><img src="assets/4300.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit Hallowing M4. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/4300

### Description

This is Hallowing..this is Hallowing... Hallowing! Hallowing! 

Following up on 2018's most-successful-skull-shaped development board, we UPPED our -skull-shaped development board game, and re-spinned (re-spun?) the HalloWing M0 into the HalloWing M4 with MORE of everything that makes this the spoooookiest dev board.

Are you the kind of person who doesn't like taking down the skeletons and spiders until after January? Well, we've got the development board for you. This is electronics at its most spooky! The Adafruit HalloWing M4 is a skull-shaped ATSAM521 board with a ton of extras built in to make for an adorable wearable, badge, development kit, or the engine for your next cosplay or prop.

On the front is a cute 1.54" sized 240x240 full color IPS TFT. Compared to the HalloWing M0's 1.44" 128x128, this has 4x as many pixels and is IPS for great color and brightness. Our default example code has our new fully-customizable spooky eye demo running but you can use it for anything you like to display in glorious color.

There's also 4 fang-teeth below the display, these are analog/capacitive touch inputs with big alligator-clip holes.

On the reverse is a smorgasbord of electronic goodies:

* ATSAMD51G18 @ 120MHz with 3.3V logic/power - 512KB of FLASH + 192KB of RAM, can run Arduino or CircuitPython super fast
* 8 MB of SPI Flash for storing images, sounds, animations, whatever!
* 3-axis accelerometer (motion sensor)
* Light sensor, reverse-mount so that it points out the front
* Mono Class-D speaker driver for 4-8 ohm speakers, up to 1 Watt, connected to a 12-bit DAC on the SAMD51
* Four side-light NeoPixel LEDs for cool underlighting effects
* LiPoly battery port with built in recharging capability
* USB port for battery charging, programming and debugging
* Two female header strips with Feather-compatible pinout so you can plug any FeatherWings in
* JST ports for Neopixels, sensor input, and I2C (you can fit I2C Grove connectors in here)
* 3.3V regulator with 500mA peak current output
* Reset button
* On-Off switch

OK so technically it's more like a really tricked-out Feather M4 Express than a Wing but we simply could not resist the HalloWing pun.

You can use the Hallowing similarly Feather M4 Express, it's got the same chip although the pins have been rearranged. We've got both Arduino and CircuitPython build support for it so you can pick your favorite development language! The extra 8 MB of SPI Flash is great for sound effects projects where you want to play up to 3 minutes of WAV files.

On each side of the Hallowing are JST-PH plugs for connecting external devices. The 3-pin JSTs connect to analog pins on the SAMD21, so you can use them for analog inputs. We label one for NeoPixel and one for Sensors since we think most people will have one of each. The 4-pin JST connector connects to the I2C port and you can fit Grove connectors in it for additional hardware support.

Does not come with a Lipoly battery! We recommend our 350mAh or 500mAh batteries but any 3.7/4.2V Adafruit Lipoly will do the trick.

Comes fully assembled and ready to be your spooky skull friend. We install the UF2 bootloader on it so updating code and converting it to CircuitPython is easy.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
