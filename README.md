

# CC1352R SensorTag Demo

## Overview


This sample demonstrates some of the capabilities of the CC1352R SensorTag by
exercising GPIO output, GPIO input, as well as I2C and SPI I/O with the on-board
sensors.

## Requirements


## Building, Flashing and Running

```
.. zephyr-app-commands::
   :zephyr-app: samples/boards/ti/cc1352r_sensortag
   :board: cc1352r_sensortag
   :goals: build flash
   :compact:
```

## Sample Output
=============


After reset, the screen will the RGB block


```        
         uart:~$ *** Booting Zephyr OS version 2.4.99  ***
        [00:00:00.130,798] <err> lis2dh: Failed to read chip id.
        [00:00:00.136,199] <inf> net_config: Initializing network
        [00:00:00.236,206] <inf> net_config: IPv6 address: 2001:db8::1
        [00:00:00.236,297] <inf> net_config: IPv6 address: 2001:db8::1
        [00:00:00.237,030] <inf> sample: Display sample for DISPLAY
```
![IMG_20210325_195544](https://user-images.githubusercontent.com/4081906/112469389-64c95080-8da4-11eb-9529-1de827a2e16b.jpg)
