## Adafruit TXB0104 Level Shifter Breakout PCB
<a href="http://www.adafruit.com/products/1875"><img src="assets/image.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

This is lovely chip: the TXB0104 bi-directional level converter! This chip perform bidirectional level shifting from pretty much any voltage to any voltage and will auto-detect the direction. Only thing that doesn't work well with this chip is i2c (because it uses strong pullups which confuse auto-direction sensor) or control lines with a lot of capacitance on them. If you need to use pullups, you can but they should be at least 50K ohm - the ones internal to AVRs/Arduino are about 100K ohm so those are OK! Its a little more luxurious than a 74LVX245 but if you just don't want to worry about directional pins this is a life saver!

Since this chip is a special bi-directional level shifter it does not have strong output pins that can drive LEDs or long cables, it's meant to sit on a breadboard between two logic chips! If you do not need instant bi-directional support, we suggest the 74LVX245 as below which has stronger output drive.

PCB files for the Adafruit TXB0104 Level Shifter Breakout. The format is EagleCAD schematic and board layout
- https://www.adafruit.com/product/1875

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

All text above must be included in any redistribution

Designed by Limor Fried/Ladyada for Adafruit Industries.
Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional information.
