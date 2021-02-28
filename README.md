# Arduino Based Volume Control System

This is a system for controlling a PGA4311 or PGA2311 with an Arduino.
 

## Supported features

 * Rotary encoder volume control with push button mute
 * Control of PGA4311 or PGA2311 volume controllers
 * EEPROM volume save state
 * Volume scaling function for smoother volume transitions
 * Limiting on maximum volume for PGA4311 control registers
 * Digital I/O used: 6 pins
 * Serial debug provided if desired
 * Code approximately 6 kB incuding serial debug


## Intended operation

To use this code, you simply need import it to you
Arduino IDE and ensure that the dependent library
are available.  You should choose which pins meet your
needs and set them in the #define section.  You can
reverse the operation of some pins.

PGA mute pin need pull down 10k resistor to GND.

You might find it prudent to trim this code to the
feature set you are looking for rather than use
it with all the conditional compilation.  That would
clean it up quite a bit and make it simpler to debug.
As is clear, this code has a fair bit of flexible
functionality, but it is rather a mess.
 

## IMPORTANT
   
Release of this code in no way implicates that any 
product designed by myself or any company that I am
involved with is constrained in any way to the methods
and / or implications of functionality, expressly or
implicitly, based on the code contained herein.  The code
presented here is intended as an as-is instructional 
collection of potential methods that may or may not be
fit for any application.

