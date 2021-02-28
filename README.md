# SSI2130-Oscillator
Design Team: Ryan Laur, Daniel Louis, Sahil Patel, Dieter Steinhauser, Cale Woodward, et al.

This repository contains documentation for an Oscillator designed using the SSI2130 chip. The intended application is for use as an audio synthesizer. The MIDI Converter used the design "MIDI2CV" by Larry McGovern (available for free under the GNU General Public License via <https://github.com/elkayem/midi2cv>).

## Parts
### MIDI-Converter:

* Arduino Nano
* 6N138 Optocoupler
* 2x MCP4822 12-bit DACs
* LM324N Quad Op Amp (using alternate?)
* Diode (1N4148?)
* 220, 500, 3x1K, 7.7K (3K+4.7K), 10K Ohm resistors
* 3x 0.1 uF ceramic capacitors
* 5 pin MIDI jack
* 7x 4mm banana plug jacks
* 3-pin header and jumper


### Oscillator:

* SSI2130
