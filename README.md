Wrapper for NRAO's Valon_synth package for controlling the Valon 5007
Synthesizer. Allows console based control of the Valon 5007 unit from the ROACH
control computer.

Requirements:
=============

[valon_synth][] and its dependencies


Usage:
======

`$ valon [options] [freq]`

If no frequency is provided, the current frequencies are read from the Valon
Synth. This wrapper only supports one input frequency, and if both the -a and -b
flags are used, the input frequency is applied to both.

Options:
========

*    `-h, --help`         show this help message and exit

*    `-a, --synth-a`      Use Synth A

*    `-b, --synth-b`      Use Synth B

*    `-t TTY, --tty=TTY`  Set Serial Port. Default is /dev/usbTTY0

*    `-v, --verbose`      Make the script verbose

*    `-f, --flash`        Write frequencies to non-volatile memory




[valon_synth]: https://github.com/nrao/ValonSynth
