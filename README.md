# Gameboy Zero

1. Download the latest pre-made image (https://github.com/sixteenbit/gameboy-zero/releases)
1. Unzip so that you have an .img file
1. Use [Etcher](https://etcher.io/) or [Apple Pi Baker](https://www.tweaking4all.com/software/macosx-software/macosx-apple-pi-baker/) to copy img to SD card
1. Create a blank file named `ssh` on the root of the card which enables ssh (optional)
1. Create a file named `wpa_supplicant.conf` on the root of the card with your WiFi credentials. [Example](https://github.com/sixteenbit/gameboy-zero/blob/master/wpa_suplicant.conf). (optional)

## What's in the box?

* GPIO controller settings for Retrogame
* Settings for USB audio
* Recommended overclocking from [RetroPie](https://retropie.org.uk/docs/Overclocking/#raspberry-pi-zero)
* Overall optimizations for gameplay
* Custom splashscreen
* Theme optimized for smaller screens
* Localization updated to English (US)

# GPIO Pins

This image of RetroPie is pre-configured to use Retrogame to setup our GPIO controller. If you need to make some customizations, edit `/boot/retrogame.cfg`. For more information, please see [Configuring Retrogame](https://learn.adafruit.com/retro-gaming-with-raspberry-pi/configuring-retrogame)

![GPIO Pins](https://raw.githubusercontent.com/sixteenbit/gameboy-zero/master/img/GPIO.png "GPIO Pins")
