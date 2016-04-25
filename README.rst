
LDmicro is a ladder logic editor, simulator and compiler for 8-bit
microcontrollers. It can generate native code for Atmel AVR and Microchip
PIC16 CPUs from a ladder diagram.


Building LDMICRO
======
LDmicro is build using Microsoft Visual C++ compiler. Simply execute

make.bat

from visual studio command prompt and see everything build.


Multiple Perl Scripts are executed by the batch files. In order to execute
these scripts, you need perl. I am using ActivePerl Community Edition

http://www.activestate.com/activeperl

The make files use GNU utilities which are not available on windows by default.
Download GNU utilities for Win32

http://unxutils.sourceforge.net


Changes made to original version of ldmicro:
======

1. Added support for Atmega328 microcontroller(Arduino)
2. Added PWM support for Atmega16 on OC2(pin 21)

