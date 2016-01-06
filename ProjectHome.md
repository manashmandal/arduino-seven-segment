# Welcome To The Arduino 7 Segment Display Library #


---

## This Project has moved to Github! ##
http://github.com/supercrab/arduino-seven-segment

---


This library which provides easy control of 7 segment (non serial) LCD and LED displays using a minimum of 2 digital outputs.

The library only works with parallel displays, where each segment on the display has a single pin to control it.  For example, if your screen can display 8888 but has less than 7 + 7 + 7 + 7 = 28 pins on the back, then you probably have a serial controlled screen and this library is not for you.  If your display explicitly state it is serial or has an SPI interface then this library is not for you.

The best thing about using a controller for your LED/LCD screen is that you only about 2 arduino outputs to control your screen, keeping all you other outputs for more important things!

This library can also be used to control LEDs which are not part of a 7 segment display.  However, if you want to do this, there is a much better library that implements a variety of features, including PWM for LED brightness, visit http://code.google.com/p/arduino-m5451-current-driver/

## Download Code ##

**You can conveniently download the whole project here:**

http://supercrab.co.uk/content/SevenSegment.zip


## Code in Action ##

Here's a youtube video I made of the driver running the 4 Digit Demo program:

<a href='http://www.youtube.com/watch?feature=player_embedded&v=nGXTJL51D6Q' target='_blank'><img src='http://img.youtube.com/vi/nGXTJL51D6Q/0.jpg' width='425' height=344 /></a>