Java Apple Computer Emulator
====

*A Heavily modified Jace-3.1, did not seem to fit or run as solid, so I remodified jace-2.
*make sure ./home is run/sourced to set JAVA_HOME the use of it along with building is critical the included Java is used.
*apt add for codespaces assures graphics work, even though it autoboots.
*First published, git of anything like this, I'll say my first, so if It doesn't work, I never get fan-mail, so give me a ticket!
*Thanks to jace team, DS's, Interchat#17, Magviz.ca & all the other motivators and folks that can code there way out of a wet_paper_sack();
*changed repository name to fit better
./start should do the magic, if not it outlines execution orders. Don't worry I'm top on the list & I'm still alive.


Download:

* [See releases page for most recent](https://github.com/badvision/jace/releases)

To Run:

* See [run.sh](run.sh)

or `java -jar Jace.jar`

To Build:

* See [build.sh](build.sh)

Jace is a java-based Apple //e emulator with many compelling features:
* NEW: Built-in IDE for writing basic and assembly programs, using ACME to compile and execute directly without leaving the emulator.
* Disk and Mass-storage (hard drive, 3.5 floppy) images
* Joystick and Mouse are fully supported (Joystick can be emulated with either keyboard or mouse, Java doesn't have native joystick support
* All graphics modes are supported, including Apple RGB "Mixed" and B&W modes.
* Fullscreen and windowed modes supported
* PassPort MIDI support for Ultima V
* MetaCheat allows quick and easy ability to find and alter active memory
* MetaCheat also provides a live heat-map showing all RAM activity, color coded to indicate read, write or CPU execution -- Perfect for reverse engineers
* Optional Debugging rom (][DB) can be enabled for a more powerful monitor
* Super serial emulated as a tcp/ip port
* Mockingboard and Phasor support
* Highly flexible configuration allows any combination of cards and many extra options. You can even alter configuration while the emulation is running!

![Airheart](https://sites.google.com/site/brendanrobert/_/rsrc/1327073239228/projects/jace/airheart.png?height=250&width=400)
![Color swatches](https://sites.google.com/site/brendanrobert/_/rsrc/1327073239228/projects/jace/colors.png?height=223&width=400)
![Desktop II](https://sites.google.com/site/brendanrobert/_/rsrc/1327992588666/projects/jace/AppleIIDesktop.png?height=265&width=400)

More information here: https://sites.google.com/site/brendanrobert/projects/jace
