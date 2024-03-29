# ao-fec: convolutional FEC code
Copyright (c) 2012 Keith Packard <keithp@keithp.com>

This code is extracted from the AltOS repository
<git://git.gag.com/altos>. It performs Forward Error
Correction encoding and decoding, using a rate 1/2 limit 4
convolutional code with a Viterbi-style decoder.

This code is compatible (tested) with the hardware FEC in
the TI CC1111 radio chip. Because of this, the interface is
a bit awkard. Please see the comments in the source files
for the API details.

# Acknowledgments

Thanks to Keith Packard for writing this, and for helping me
debug and test it.

# License

This code is licensed under the "GNU General Public License
version 2". See the file `LICENSE.txt` in this codebase for
licensing terms.
