# Corne Layout - Snazzy-Boi

Notes for getting QMK to build custom corne layout, this in no way is totally
comprehensive or to say I am anything close to an expert. Just a easy
way for me to log my build and compilation struggles and successes that
hopefully will help others on the way!

<!-- vim-markdown-toc GFM -->

* [Overview](#overview)
* [Building](#building)
	* [1. Diodes](#1-diodes)
	* [1. Hotswap Switch mounts](#1-hotswap-switch-mounts)
	* [1. LEDs](#1-leds)
* [Compiling](#compiling)
* [Flashing](#flashing)
* [Extras](#extras)
* [References](#references)

<!-- vim-markdown-toc -->

## Overview

Building your custom hex files can be a pain so using github actions and
CI should make the process easier.

## Building

Building the keyboard was fairly simple. I went through [boardsource](https://boardsource.xyz) to purchase the components 
and it all arrived quickly. Following the instructions on [foostans
project](https://github.com/foostan/crkbd) and they are extremely well
put together and easy to follow (if you read unlike what I did).

### 1. Diodes

TBD

### 1. Hotswap Switch mounts

TBD

### 1. LEDs

TBD

## Compiling

This project uses GitHub actions to build out the .hex file for flashing
the keyboard.

## Flashing

You will have to use the [QMK ToolBox](https://github.com/qmk/qmk_toolbox) tool to flash the keyboard or use
the [QMK CLI](https://beta.docs.qmk.fm/cli/cli)

## Extras

- [Image2Cpp](https://javl.github.io/image2cpp/)
- [QMK Logo Editor](https://joric.github.io/qle/)

## References

- [Example of custom build](https://jing.io/projects/corne-custom-keyboard/)
- [Building First Firmware](https://beta.docs.qmk.fm/tutorial/newbs_building_firmware)
