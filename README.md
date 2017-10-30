TFT_22_ILI9225
==============

**Version 1.2.6, released 2017-10-27, adds support for all platforms.**

**Version 1.2.3, released 2017-10-22, adds backlight brightness control.** Credit: [miro1360](https://github.com/miro1360)

**Version 1.2.1, released 2017-09-18, fixed color table shift error.**

**Version 1.2.0, released 2017-01-18, speeds up Hardware SPI significantly.**

This is a library for the ILI9225 TFT display products, forked from the screen_4D_22_library library. Ability to
use GLCD fonts has been added and the syntax has been changed to match the Adafruit libraries somewhat.

This library works with the ILI9225 based 2.2" 176x220 TFT LCD shields commonly found on eBay. Note
that there is a commonly available 2.2" 240x320 TFT module very similar in appearance but using the
ILI9341 driver.

<img src="https://raw.githubusercontent.com/Nkawu/TFT_22_ILI9225/master/images/ILI9225_TFT_front.jpg" alt="Front" width="300">
<img src="https://raw.githubusercontent.com/Nkawu/TFT_22_ILI9225/master/images/ILI9225_TFT_back.jpg" alt="Back" width="300">

##To install the library:

###Arduino Library Manager:
* In the Arduino IDE menu, select:
* Sketch
* Include Library
* Manage Libraries...
* In the resulting **Library Manager** dialog:
* Enter **"9225"** in the search filter field _(Filter your search...)_
* Select **TFT_22_ILI9225" in the list
* click on the **Install** button

###Direct Install:
* Click the **Download ZIP** button on the right to download **TFT_22_ILI9225-master.zip**
* Extract the ZIP file to the library folder your *arduinosketchfolder*/libraries/ folder. You may need to create the libraries subfolder if it's your first library.
* Rename the uncompressed folder from **TFT_22_ILI9225-master** to **TFT_22_ILI9225**
* Restart the Arduino IDE

Look at the included "Basic_Demo" example sketch for sample code and the Wiki for documentation.
