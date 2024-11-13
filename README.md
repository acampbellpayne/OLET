# OLET
BOM and documentation for the Orca Livecoding Environment Terminal: a tiny computer built from OTS components made to run orca-c (https://github.com/hundredrabbits/Orca-c).
The current design is intended to fit inside a eurorack modular synthesizer, but a standalone design would be possible using a small enclosure with breakout ports.

The required components are:
- [ ] raspberry pi zero
- [ ] usb hub
- [ ] screen
- [ ] power supply
- [ ] euro panel
- [ ] keyboard
- [ ] USB-MIDI interface

Future goals include designing a simple interface board that breaks out MIDI from UART on the Raspberry Pi, and eventually a custom design that breaks away from the Raspberry Pi entirely.
It's most likely that this would involve using a Microchip SAM9X60 or similar microprocessor running a custom linux distro built with Yocto or Buildroot.
