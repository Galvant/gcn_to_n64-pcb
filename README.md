GCN to N64 PCB
==============

This repository contains the KiCAD PCB project files for the Gamecube controller
to Nintendo 64 adapter.

The associated firmware project can be found on GitHub at 
https://github.com/brownan/Gamecube-N64-Controller

Pre-assembled boards will be available shortly at [Galvant Industries](www.galvant.ca)

Project Details
---------------

This simple circuit board allows one to use a Nintendo Gamecube controller with a Nintendo 64 console. The primary motivation for this is simple: The Gamecube controller is far superior to the N64 one, especially the analogue sticks. As N64 controllers age, their analogue sticks become loose, eventually losing the ability the fully actuate which can prevent in-game characters from being able to run/preform tight turns/etc.

The board is a fairly simple design featuring an Atmel ATMega328 with the Arduino bootloader loaded on. Located beside each of the through-holes for the cables are mechanical stress relief holes to affix the cables down.

The best place to source the N64 and GCN connectors and cables will probably be to just buy an extension cable off eBay or something and cut the cable down. In addition, you will then need to map which conductor corresponds to which connector pin number, and thus which conductor goes where on the circuit board. A multimeter will be best for this as I found my extension cable did not have the same pin-cable colouring scheme as the official Nintendo controllers do.

The current firmware maps the X and Y buttons to C-left and C-right, and the C-stick straight maps to the C-buttons. This may be changed in the future in order to provide A-B turbo functionality to the XY buttons, while a Smash Bros specific buttons mapping could also be made to closer emulate the control scheme in Melee (ie C-stick for smash attacks, XY for jumping, etc).

Video
-----

A basic video of the adapter in action can be [found on the author's YouTube channel](http://www.youtube.com/watch?v=secM9QJF3xM).

License
-------

This work is released under the Creative Commons Attribution-Sharealike 3.0 license. 
See http://creativecommons.org/licenses/by-sa/3.0/ or the included license/LICENSE.TXT file 
for more information.

Other
-----

All Nintendo trademarks are theirs, etc etc.
