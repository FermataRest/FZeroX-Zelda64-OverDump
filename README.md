# FZeroX-Zelda64-OverDump

<p align="center">
  <img src="images/f-zero-x-zelda-64-overdump-cart-front.jpg" width="800">
</p>

<p align="center">
  <i>Nintendo 64 development cartridge containing a retail build of F-Zero X and an overwritten early Zelda 64 overdump.</i>
</p>

## Overview

This repository documents a Nintendo 64 development cartridge containing a retail build of **F-Zero X**, with an overdump of a very early version of **The Legend of Zelda: Ocarina of Time**.

The surviving Zelda 64 data dates from around the time of Nintendo's **SpaceWorld 1997** tradeshow.

What makes this cartridge unusual is that a substantial amount of the early Zelda 64 data remains intact. The recovered data includes **maps, textures, text, and other game resources**.

Unfortunately, the cartridge was subsequently overwritten with the retail F-Zero X data. As a result, important portions of the original Zelda 64 build are no longer present, including:

- Character models
- Game code
- Audio data

The cartridge was acquired from a former Nintendo employee.

## Zelda 64 Data Location

The surviving Zelda 64 data begins at:

```text
0x1000000# overdump-extract-scenes

This repo contains the source code for the software I wrote to help me datamine the F-Zero X overdump: specifically, this code is for locating, extracting, and fixing the surviving scene files. For those more interested in how I figured out what to do, [check out the companion article](https://z64.me/post/data-mining-the-overdump/).

**The F-Zero X overdump is not included; you must provide your own copy.**

## How to use

This is intended to be run on Linux or WSL. It is possible to build and run it on Windows as well, but not with the provided build script.

```
cd ~
git clone https://github.com/z64me/overdump-extract-scenes.git
cd overdump-extract-scenes
git submodule update --init
./build.sh
bin/extract-scenes "/path/to/your/copy/of/the/overdump"
```

If successful, a new folder named `scenes` will be made, containing every converted scene.

