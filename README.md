Intel Galileo Muzzley Demos
========================

Control a led strip with your mobile device (iOS and Android) using an [Intel Galileo Board](http://arduino.cc/en/ArduinoCertified/IntelGalileo)

This demos use [Muzzley](http://www.muzzley.com) for the Mobile <-> Galileo signaling and mobile views development.

[![Demo preview](http://img.youtube.com/vi/Qoxn3yODUCI/0.jpg)](https://www.youtube.com/watch?v=Qoxn3yODUCI)


### About the demos

Two demos are available:
  - Galileo Pin Debugger
    This demo allows the user to read and write to the galileo board pins. Allowed values are 0 and 1 and the allowed directions are In and Out. Beware that you can only change a value if the direction is set to Out.
    By default the galileo pins 4, 5, 6, 7, 8, 9 and the on-board LED were made available (GPIOs 28, 17, 24, 27, 26, 19, 3).
    Clicking on a pin will show you a popup which will allow you to do such operations. You can try for instance connecting a LED to a specific pin and use the mobile device to turn it on and off setting the direction to out and switching between values 0 and 1.

  - Digital RGB Ledstrip Control
    This one allows the user to control a LED strip. You can fill it with colors or play some colorful animations. Picking the color, selecting an effect or adjusting brightness will trigger the animation with the selected parameters. The color palette is available on clicking the custom color button, you can try slowly dragging your finger in the color palette and watch the LED strip changing colors in real time.


### Hardware Requirements

In order to run those demos it's required:
  - Intel Galileo Board
  - Micro SD card
  - Digital RGB Led Strip
  - External power supply for the led strip (If the ledstrip is long)

[Wiring diagram](https://raw.github.com/v0od0oChild/MuzzleyGalileoDemos/master/docs/wiring_diagram.png)


### Software Requirements

It is required:
  - Linux image in the SD card
  - Muzzley account
  - NodeJs
  - Npm and its dependencies
  - Git


### Documentation

Download the Installation/usage guide here:

[Muzzley Galileo Manual](https://github.com/v0od0oChild/MuzzleyGalileoDemos/blob/master/docs/manual.pdf?raw=true)



### Image File

If you prefer you can download our ready to run image. This image contains linux with the essencials to run the demos.

[Download the demo image file](https://cdn.muzzley.com/intel/muzzley_galileo_1.4.1.gz)

See the documentation for the installation/usage guide.



### Screenshots

Mobile views

[Galileo pin debugger](https://raw.github.com/v0od0oChild/MuzzleyGalileoDemos/master/Screenshots/debugger_preview.png)

[Galileo led strip](https://raw.github.com/v0od0oChild/MuzzleyGalileoDemos/master/Screenshots/ledstrip_preview.png)