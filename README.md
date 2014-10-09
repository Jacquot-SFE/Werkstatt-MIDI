# Moog Werkstatt-01 MIDI interface 

GitHub repository supporting my blog post at sparkfun.com.
[https://www.sparkfun.com/news/1617](https://www.sparkfun.com/news/1617)

----------------------------

Dependency
---

This was written using the Arduino MIDI library from FortySevenEffects.  It was using [version 4.2, hash 352e3d10fb](https://github.com/FortySevenEffects/arduino_midi_library/commit/352e3d10fbcaa8a1d603fa822c026404dd18014c).

Repository Contents
-------------------

* **/Firmware** - Arduino project source code
	* **/werkstatt-midi/** is the MIDI-to-CV code.  
	* **/dac-integration-test/** is simple test code to verify that both of the MCP-4725's are at different I2C addresses.
* **/diagrams** contains the SVG hookup diagram for the circuit
* **/theory** contains background documents  

Bill Of Materials
----------------
* [Moog Werkstatt](https://www.sparkfun.com/products/13146) Monophonic analog synthesizer
* [Pro-Micro](https://www.sparkfun.com/products/12640) Arduino compatible microcontroller board
* [MIDI Breakout](https://www.sparkfun.com/products/9598) MIDI I/O plugs
* [MCP-4725 DAC](https://www.sparkfun.com/products/12918) 12-bit I2C digital to analog converter



Version History
---------------

* [7fac8c0](https://github.com/Jacquot-SFE/Werkstatt-MIDI/commit/7fca8c0658635085f6b7fcb229df15732892a324) Initial commit 


License Information
-------------------
The individual hardware pieces are released under [Creative Commons ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/).

Ordinarily, we'd be using the beerware license for the firmware.  However, the FortySevenEffects MIDI library is GPL V3.  Since we're statically linking to it, that likely means the result needs to be GPL V3 as well.

Distributed as-is; no warranty expressed or implied.