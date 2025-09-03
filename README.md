# Audio Player for Synthesizer
An audio player for a modular synthesizer based on a cheap 'Kebidu music speakers' module with FM radio, USB, micro SD, Bluetooth and aux-in modes.
This was inspired by the [Tesseract Modular 'Low Coast'](https://www.tesseractmodular.com/eurorack-modules/low-coast/) module which simply provides two Eurorack-level outputs, one for each of the stereo channels of the module.

This version also provides a mono mix output and has trigger inputs for the transport controls - play/pause, next station/track & previous station/track.

<img width="25%" height="25%" src="https://github.com/clarionut/Audio-Player-for-Synthesizer/blob/main/pictures/Audio%20Player%20Panel.jpg">

I'm not sure that this will be a particularly useful synth module, but I wanted to experiment using FETs as switches to allow external control. Also the Kebidu units are very cheap - I got two for around £5 including shipping.

### Details
The Schematics folder contains pictures of the kicad schematic, the stripboard layout I used to build the module and a proposed PCB layout. Note that I haven't had the PCB fabricated, so use this at your own risk! The kicad project itself is in the AudioPlayer folder.

The only tricky part of the build was soldering the source and drain legs of the 2N7000 FETs across the switches. The solder pads are very small, so a fine-tipped soldering iron and a steady hand are needed! I've included a [photo showing the orientation of the FETs] on my module
