# huepl

Perl script to control [Philips Hue](http://www.meethue.com) light bulbs.

Forked from http://www.floodgap.com/software/huepl/ to add some custom changes.
These are mostly for my personal use, but maybe you find some of them,
e.g. groups handling, helpful. 

![Screenshot](/doc/huepl_scrot.png?raw=true "Screenshot")

## Usage

See the inbuilt help or the original [website](http://www.floodgap.com/software/huepl/) for documentation.

## Changes

- Added 256 colours support, hardcoded (Does not work if your terminal does not support it) 
- Changed the output to colourify status and brightness
- Translated to German (hardcoded) 
- Added the `groups` command to list groups, similar to `lights`, does not take arguments
- Added the `g` command, prepend it to any command, e.g. `g 2 green` or `g 3 xy 0.4 0.2`

## License

As per the original license, this fork is also licensed under the The Floodgap Free Software License (FFSL).
See COPYING for details
