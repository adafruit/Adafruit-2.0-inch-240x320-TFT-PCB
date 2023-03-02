## Adafruit 2.0" 320x240 Color IPS TFT Display with microSD Card Breakout PCB

<a href="http://www.adafruit.com/products/4311"><img src="assets/4311.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit 2.0" 320x240 Color IPS TFT Display with microSD Card Breakout. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/4311

### Description

This gorgeous IPS display breakout is the best way to add a small, colorful, and bright display to any project, with excellent visibility from any angle. Since the display uses 4-wire SPI to communicate and has its own pixel-addressable frame buffer, it can be used with every kind of microcontroller. Even a very small one with low memory and few pins available!

The 2.0" display has 320x240 color pixels. Unlike the low cost "Nokia 6110" and similar LCD displays, which are CSTN type and thus have poor color and slow refresh, this display is a true TFT! Not only that, but its an IPS display for vivid color and high-angle visibility. The TFT driver (ST7789) can display full 18-bit color (262,144 shades), but almost all drivers will use just 16-bit color. The TFT will always come with the same driver chip so there's no worries that your code will not work from one to the other.

The breakout has the TFT display soldered on (it uses a delicate flex-circuit connector) as well as a ultra-low-dropout 3.3V regulator, auto-reset circuitry, and a 3/5V level shifter so you can use it with 3.3V or 5V power and logic. We also had a little space so we placed a microSD card holder so you can easily load full color bitmaps from a FAT16/FAT32 formatted microSD card. The microSD card is not included, but you can pick one up here.

Of course, we wouldn't just leave you with a datasheet and a "good luck!" - we've written a full open source graphics library that can draw pixels, lines, rectangles, circles, text, and bitmaps as well as example code. The code is written for Arduino but can be easily ported to your favorite microcontroller! Wiring is easy, we strongly encourage using the hardware SPI pins of your Arduino as software SPI is noticeably slower when dealing with this size display.

New! As of February 2023, this display breakout also features an 18-pin "EYESPI" standard FPC connector with flip-top connector. You can use an 18-pin 0.5mm pitch FPC cable to connect to the display over SPI and I2C, respectively. Great for when you want to skip soldering all those headers. 

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
