# Eurorack Power Supplies

schematics for eurorack power supplies

## Setup

* copy libraries from *schematics/libraries* to eagle libraries folder
* copy schematics to eagle project folder
* open project
* activate libraries with right click and *use* in library manager

## Notes

* To avoid oscillation problems when using DKMW30f-12:
  * Replace R6 with wired connection
  * Don't solder in C3

## BOM

### DC DC Converter Options

#### 12V

* 30W: https://www.mouser.de/ProductDetail/MEAN-WELL/DKMW30F-12/?qs=%2Fha2pyFadugPfVRQAxI4Iwf31KvWSSQ5yO6OlzoqYdGM367f8%2FWl4w%3D%3D
* 15W: https://www.mouser.de/ProductDetail/MEAN-WELL/DKMW15F-12/?qs=%2Fha2pyFaduiYoYgxwNsfdZ5VubX0%252Bab1un6BH80socxHllnzIFJ%2FvQ%3D%3D

#### 5V

* 1A: https://www.reichelt.de/dc-dc-wandler-tsr-1-1-w-5-v-1000-ma-sil-to-220-tsr-1-2450-p116850.html?search=tsr+1-2450
