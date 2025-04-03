---
layout: default
---

## Project status Quo
<!-- =============================================================================== --> 

I am building an all-sky camera using a Raspberry Pi 5 along with a custom-designed Altium PCB. Currently, the components exist in two separate repositories, but I will be combining them once i have the network up and running from prototype!

# progression list to date.
1. All items have been procured.
2. A repository has been solected based on hardware requiments and amended for sensor.
3. Sensor has ben designed and orded from JLPCB!
4. Test network and upload images!
![image](https://github.com/user-attachments/assets/7c9247cb-81ff-4be3-af64-e61accaadfd1)
A capture from a night sky cam, but definitely not from an Houn ville

## Requirements for Allsky Camera for PI5 amended for SHT31 Temperature and humdidty sensor 

In order to run the Allsky software, you will need:

* A Raspberry Pi Zero 2, Pi 2, Pi 3, Pi 4, Pi 5, or Le Potato.
* A version of the Raspberry Pi OS. Other operating systems like Ubuntu are NOT supported. If possible, use the newest Bookworm 64-bit release of Pi OS with the "Desktop" version. Bullseye will also work. __Buster support will be dropped in the next major release__.
* A camera:
    * Any ZWO camera sold before February 1, 2025,
    * or one of the following cameras:
        * Raspberry Pi:
            * HQ (IMX477 sensor)
            * Module 3 (IMX708 sensor)
            * Version 1 (OV5647 sensor; NOT RECOMMENDED: 0.9-second maximum exposure)
        * Arducam:
            * 16 MP (IMX519 sensor)
            * 64 MP (arducam_64mp sensor)
            * 462 (arducam-pivariety sensor)
            * 64 MP Owlsight (OV64a40 sensor)
        * Other:
            * Waveshare imx219-d160 (IMX290 sensor)
            * OneInchEye IMX283 (IMX283 sensor)
            * IMX290 60.00 fps
            

This is the source code and primary credit for SW:
 [on Instructables](http://www.instructables.com/id/Wireless-All-Sky-Camera/).
### Humidity and Temperature Sensor - SHT31

This is a basic humidity and temperature sensor utilizing the SHT31 chip. The design is similar to that of Adafruit. This PCB is intended to work in conjunction with the all-sky camera.
<img src="https://raw.githubusercontent.com/hughsLab/my-github-page/main/assets/images/pcb-met.png" alt="PCB Met sensor" width="250" />



_Work in progress_

[back](./)