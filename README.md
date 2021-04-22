# NES-Power-Board
A PCB that will fit in place of the stock NES frontloader's RF module.
***
This PCB replaces the stock RF modulator box on a frontloader NES. It has different connector options for outputting audio and video, as well as a breakout for the channel select switch.

*** This is a fork of Spink's NES Power Board with some fixes to make it compatible with the NESRGB mod. The following is supported:

* NESRGB output directly to an 8-pin mini DIN connector, composite and mono sound to the side output jacks. (Requires existing RGB mod)
* NESRGB + composite using a Retrofixes SNES style multiout connector.  (Requires existing RGB mod) 

The first option requires no modification to the chassis. The SNES option requires some chassis modification, but it is minimal.

This PCB is designed specifically with Tim Worthington's NESRGB board in mind. The channel select switch has a breakout so that it can be used as a palette selector switch.
***

Currently native composite video output is not supported. This should be possible by making changes to the existing schematic and hopefully that will be possible in a future update.