# Mazda-3-OpenAuto-Schematic

This is the schematic of an OpenAuto build for a Mazda 3 2010 BL.
The diagram mainly covers the power distribution to all the main parts:
- USB Hub (displayed as a port in the scheme)
- Raspberry PI
- DC-DB converter (included in the custom library)
- Timer relay (included in the custom library)
- Arduino micro (for decoding the steering wheel buttons)

But it also covers the logic for inverting the inputs and isolate it. It takes a few inputs:
- 12V from the battery
- 12V input from the lights
- 12V for reversing
- 12V after-contact to toggle the whole circuit