## Adafruit PMSA003I Air Quality Breakout - STEMMA QT / Qwiic PCB

<a href="http://www.adafruit.com/products/4632"><img src="assets/4632.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit PMSA003I Air Quality Breakout - STEMMA QT / Qwiic.

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/4632

### Description

Breathe easy, knowing that you can track and sense the quality of the air around you with this Adafruit PMSA003I Air Quality Breakout. This sensor is great for monitoring air quality, in a compact plug-in format.

Best of all, unlike almost all other sensors we've seen that are UART interface, this one is I2C interface, which makes it a great match for single board Linux computers like Raspberry Pi, or even plain Arduino UNO's that normally would use software serial.

If you're an I2C fan (who isn't?), we've included two of our handy dandy SparkFun Qwiic compatible STEMMA QT connectors for the I2C bus so you don't even need to solder! Plug and play with other 'QT boards and sensors to add quick air quality sensing.

This sensor uses laser scattering to radiate suspending particles in the air, then collects scattering light to obtain the curve of scattering light change with time. The microprocessor calculates equivalent particle diameter and the number of particles with different diameters per unit volume.

The I2C data stream updates once per second, you'll get:

* PM1.0, PM2.5 and PM10.0 concentration in both standard & environmental units
* Particulate matter per 0.1L air, categorized into 0.3um, 0.5um, 1.0um, 2.5um, 5.0um and 10um size bins

As well as checksum, in binary format.

Each order comes with one fully assembled sensor module breakout, including some header if you'd like to solder it to a breadboard. The breakout board has a 5V mini boost circuit so you can power it from 3.3V and 5V and the motor will run just fine

Lastly, it wouldn't be an Adafruit breakout if it didn't come with libraries for Arduino and CircuitPython or Python that will read and checksum data, and print it out in human-readable format.

If you prefer the bare sensor module by itself, we carry it on this page.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution.
See license.txt for additional details.
