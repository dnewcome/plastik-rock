# Plastik Rock 

## About

Plastik Rock is a Pure Data patch to interface Guitar Hero and Rock Band controllers
with MIDI instruments. 

## Requirements

Plastik Rock uses the hidin PD object, which is only available on Windows. In order
to use dynamic button mapping via sending PD messages, PD version 0.43 is required.
It's possible that earlier versions will work to some degree. Due to a bug in PD
0.42 does not support features that are used for dynamically mapping controller
buttons.

## Usage

Connect the guitar controller and run the example.pd patch and read the tutorial to get started.
Analog mode in the PS2-USB driver must be enabled in order to use the whammy bar.
Most interfaces default to digital mode. If possible it's best to set the directional
mode of the adapter to button mode as it's somewhat easier to configure than using the 
POV hat.

## Future work

Support for certain additional controllers and USB interfaces is ongoing. Several 
Game controllers are available to the author so it's likely that Plastik Rock 
will support these controllers eventually. Other controllers will probably work
but may have some features that won't work correctly (typically the whammy bar).

A Linux version using the hid object should be forthcoming, but my current 
audio laptop is Windows so it may be some time before I get around to it.
