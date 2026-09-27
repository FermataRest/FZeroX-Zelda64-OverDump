# FZeroX-Zelda64-OverDump

<p align="center">
  <img src="https://raw.githubusercontent.com/FermataRest/FZeroX-Zelda64-OverDump/main/images/f-zero-x-zelda-64-overdump-cart-front.jpg" width="800">
</p>

<p align="center">
  <i>Nintendo 64 development cartridge containing a retail build of F-Zero X and an overwritten early Zelda 64 overdump.</i>
</p>

## Overview

This repository documents a Nintendo 64 development cartridge containing a retail build of **F-Zero X**, with an overdump of a very early version of **The Legend of Zelda: Ocarina of Time** from around the time of Nintendo's **SpaceWorld 1997** tradeshow.

What makes this cartridge special is that it contains surviving data from this early Zelda 64 build. The data for **The Legend of Zelda: Ocarina of Time** includes maps, textures, text, and other development resources.

Unfortunately, important portions of the original Zelda 64 data were overwritten by the later F-Zero X data. Character models, executable code, and audio are not present in the surviving data.

The cartridge was acquired from a former Nintendo employee.

## Zelda 64 Data Location

The surviving Zelda 64 data begins at:

```text
0x1000000
```

This repository documents and preserves the surviving data for further research into the development of **The Legend of Zelda: Ocarina of Time**.

---

## Cartridge

<p align="center">
  <img src="https://raw.githubusercontent.com/FermataRest/FZeroX-Zelda64-OverDump/main/images/f-zero-x-zelda-64-overdump-cart-front.jpg" width="800">
</p>

<p align="center">
  <i>Front of the F-Zero X cartridge containing the surviving Zelda 64 data.</i>
</p>

---

## Recovered Zelda 64 Data

### Asset and Resource Data

<p align="center">
  <img src="https://raw.githubusercontent.com/FermataRest/FZeroX-Zelda64-OverDump/main/images/_1.png" width="896">
</p>

The surviving Zelda 64 data contains maps, textures, text, interface graphics, and other development resources.

---

### Castle Environment

<p align="center">
  <img src="https://raw.githubusercontent.com/FermataRest/FZeroX-Zelda64-OverDump/main/images/_2.png" width="960">
</p>

Recovered early Zelda 64 environment data showing a large castle structure and surrounding terrain.

---

### Forest Environment

<p align="center">
  <img src="https://raw.githubusercontent.com/FermataRest/FZeroX-Zelda64-OverDump/main/images/_3.png" width="960">
</p>

Recovered early forest environment data, including tree stumps, terrain, paths, and surrounding forest geometry.

---

## ROM Information

### File Data

```text
System:             Nintendo - Nintendo 64
File:               F-ZERO X [CFZE].z64
BitSize:            256 Mbit
Size (Bytes):       33554432
CRC32:              68FE1CEC
MD5:                95BF2153AAAD6FAFF3FB42FECD2F0200
SHA1:               6AA870EC53602650638B50D7C89CAC026BE481F0
SHA256:             8CEF0E399C0524052B758109ABE894C709A72540A42C4A2118064A5CDDF01B6D
```

### Header Data

```text
Fixed Value 1:      0x8037
Compression Flag:   0x12
Fixed Value 2:      0x400000000F
EntryPoint:         0x00702680
Fixed Value 3:      0x000014
Unknown Value:      0x49
Boot Chip:          CIC-NUS-6106

CRC1:               0xB30ED978 (Ok)
CRC2:               0x3003C9F9 (Ok)

Reserved 1:         0x0000000000000000
Title:              F-ZERO X
Reserved 2:         0x0000000000000000
Serial:             CFZE (USA)
Version:            0x00 (v1.0)
```

---

## ROM Layout

The cartridge is a **256 Mbit Nintendo 64 ROM** containing the retail **F-Zero X** build.

The surviving Zelda 64 data begins at:

```text
0x1000000
```

The Zelda data is embedded within the later F-Zero X ROM image rather than existing as an independently bootable Zelda 64 game image.

Because the later F-Zero X data overwrote portions of the cartridge, the surviving Zelda material represents only a partial snapshot of the original development build.

---

## Historical Context

The surviving data is associated with a very early period in the development of **The Legend of Zelda: Ocarina of Time**, around the time of Nintendo's **SpaceWorld 1997** presentation.

The recovered material includes maps, textures, text, and other resources from the early Zelda 64 data preserved on the cartridge.

These resources provide material for studying the development and structure of **Zelda 64** during this period.

This is **not a complete playable build** of *The Legend of Zelda: Ocarina of Time*. The character models, executable code, and audio associated with the original Zelda 64 data were overwritten by F-Zero X.

---

## Known Surviving Data

| Category | Status |
|---|---|
| Maps | Surviving |
| Textures | Surviving |
| Text | Surviving |
| Environment data | Surviving |
| Interface / resource data | Surviving |
| Character models | Overwritten |
| Game code | Overwritten |
| Audio | Overwritten |

---

## Preservation Notes

The primary purpose of this repository is **historical preservation, research, and documentation** of the surviving Zelda 64 data.

The recovered material should be treated as development-era data rather than a complete playable version of **The Legend of Zelda: Ocarina of Time**.

The surviving resources provide a partial look at an early stage of Zelda 64 development. Further analysis may reveal additional relationships between the surviving resources and other known early Zelda 64 materials.

---

## Internet Archive Record

An archival copy of this material is preserved on the **Internet Archive**:

**[F-Zero X (Zelda 64 Overdump)](https://archive.org/details/f-zero-x-z-64-over-dump.-7z)**

The Internet Archive record identifies the item with the following topics:

```text
N64
Nintendo
Prototype
Development
Debug
Sample
```

The item description identifies the material as a development cartridge containing a retail build of **F-Zero X** and an overdump for a very early version of **The Legend of Zelda: Ocarina of Time** from around the time of Nintendo's **SpaceWorld 1997** tradeshow.

According to the archived description, the surviving Ocarina of Time data contains maps, textures, and text, while character models, code, and audio were overwritten by F-Zero X.

The Internet Archive record contains the following metadata:

```text
Item Size:       21.9 MB
Identifier:      f-zero-x-z-64-over-dump.-7z
Uploaded by:     Forest of Illusion
Upload Date:     October 7, 2022
Item Date:       January 19, 2021
```

The item is included in:

- Forest of Illusion Prototype Collection
- Software History Collection

The Internet Archive record also preserves the original reference images and provides the archived 7Z file.

---

## Repository Contents

This repository contains documentation and reference material related to the surviving Zelda 64 overdump data.

The `/images/` directory contains photographic documentation of the cartridge and screenshots of recovered Zelda 64 material.

### Images

```text
/images/
├── f-zero-x-zelda-64-overdump-cart-front.jpg
├── f-zero-x-zelda-64-overdump-cart-front_thumb.jpg
├── _1.png
├── _2.png
└── _3.png
```

---

## Related Research

The surviving data from the F-Zero X overdump has also been used by other Zelda 64 preservation and reconstruction projects.

One notable example is the **Spaceworld 1997 Ocarina of Time Recreation** project, which states that areas, dialogue, and most textures in its recreation originate from the F-Zero X overdump.

[Spaceworld 1997 Ocarina of Time Recreation](https://github.com/z64proto/sw97)

Additional Zelda 64 research and reverse-engineering resources can be found in projects such as:

- [z64me](https://github.com/z64me/z64me)
- [Zelda Reverse Engineering Team](https://github.com/zeldaret/)
- [Z64Utils](https://github.com/zeldaret/Z64Utils)

---

## Disclaimer

This repository is intended for historical research, preservation, and documentation of Nintendo 64 development material.

**Nintendo**, **F-Zero X**, **The Legend of Zelda**, and **Ocarina of Time** are trademarks and/or copyrighted works of their respective owners.
