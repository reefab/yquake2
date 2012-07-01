# Quake 2 for Raspberry PI

## Description

This is a port of the [1997 id Software Game](http://en.wikipedia.org/wiki/Quake_2) to the [Raspberry PI](http://www.raspberrypi.org/).

From Wikipedia:

> The Raspberry Pi has a Broadcom BCM2835 system on a chip (SoC),[3] which includes an ARM1176JZF-S 700 MHz processor, VideoCore IV GPU,[9] and 256 megabytes of RAM. It does not include a built-in hard disk or solid-state drive, but uses a SD card for booting and long-term storage.

This is based of the [Yamagi Quake 2 port](http://www.yamagi.org/quake2/), more
precisely, the OpenGL ES branch.

## In Action

![Console](https://github.com/reefab/yquake2/raw/raspberry/stuff/photo.jpg)

[Video](http://www.youtube.com/watch?v=lD2K1JtsNYs)

## Current State

Mostly playable but some graphical effects had to be disabled.
The sound is also disabled by default.


## Installation

### Pre-requisites

 * Raspberry PI
 * Debian Wheezy public beta
 * a 192/64 RAM split

### Packages needed

 * libsdl1.2-dev
 * libvorbis-dev
 * libogg-dev
 * zlib1g-dev
 * libjpeg8-dev

Follow the instructions from [the original README](https://github.com/reefab/yquake2/blob/raspberry/README)
to build and install.

## Notes

You can get the demo files from [Fileplanet](http://www.fileplanet.com/6584/0/fileinfo/Quake-2-Demo-v3.14)

The game should be launched as root in the console.

You might want to copy the `stuff/yq2.cfg` to the `baseq2` directory where you
installed the game to get sane settings for the Raspberry PI.
