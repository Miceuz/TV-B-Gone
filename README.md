TV-B-Gone
=========

This is my custom TV-be-gone implementation. The board was ment to fit on a standard double AA battery compartment. In general, this design was driven by what parts do I have available in my junk box, thus I've chosen Attiny44  as main microcontroller as I have plenty of them. Leds are driven by mosfets because I had some scavenged from some motherboard.

The code is from Adafruit - https://github.com/adafruit/TV-B-Gone-kit. I've removed all the codes for North American TVs and commented out the biggest codes for European TVs as Attiny44 does not have enough flash to fit them all. I've inverted PWM because I'm driving LEDs via N-channel mosfets, unlike BJTs in Adafruit version.