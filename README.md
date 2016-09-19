# Sensor

All the necessary documentation and tools to make the 6element sensor

## Overview

The 6element sensor gathers two types of data:
- affluence and waiting time
- level of waste bins per type

Both of these are gathered through a single device we'll call the sensor.


## Hardware

* The sensor is based on a [Raspberry Pi](https://www.raspberrypi.org/products/).
* **(TODO)** Affluence and waiting time data is gathered via an antenna
* Level of waste bins is gathered via a [touch display](https://www.raspberrypi.org/products/raspberry-pi-touch-display/) running [6bin](https://github.com/6element/6bin).
* **(TODO)** Data are sent either through Ethernet or a 3G dongle-based solution
* The Raspberry Pi needs to be powered via a [power supply](https://www.modmypi.com/raspberry-pi/accessories/power-supplies).
* The box around it all to protecte and make the sensor attachable to a wall is built from [6box](https://github.com/6element/6box). You'll need to buy the wood (which width? sort of wood?) and laser-cut it at a fablab.
* SD card to store the Raspbian OS image and application code


### Costs

| Item                | Where to buy                                                    | Cost     | Notes |
|---------------------|-----------------------------------------------------------------|----------|-------|
| Raspberry Pi        | https://www.adafruit.com/product/998                            | $40      |       |
| RPi Touch Display   | https://www.adafruit.com/products/2718                          | $80      |       |
| Power supply        | https://www.modmypi.com/raspberry-pi/accessories/power-supplies | £7       |       |
| 6box wood           | ?                                                               | ?        |       |
| 6box lasercut       | Cap Science                                                     | 40€/hour |       |
| micro SD Card (8GB) | https://shop.pimoroni.com/products/noobs-8gb-sd-card            | £5       |       |
| 3G Dongle           | ?                                                               | ?        | ?     |
| 3G Card             | ?                                                               | 1€/Mb    | ?     |
















