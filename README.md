# maaxboard-prebuilt
This repository contains prebuilt images for running seL4 on the Avnet MaaXBoard.

## Licence
This work is © Crown Copyright NCSC, released under a 2-Clause BSD licence.


## disk_images
This folder contains two zipped disk images, either of which can be written to an SD card (16GB or larger):
  - `maaxboard-uboot.img.zip` - Contains U-Boot, a BOOT partition for storing seL4 applications, and a FILESYSTEM partition.
  - `maaxboard-sel4-test.img.zip` - Equivalent to the image from `maaxboard-uboot.img.zip`, plus the [seL4Test](https://docs.sel4.systems/projects/sel4test/) application for the MaaXBoard preloaded in the BOOT partition.

## u-boot
This folder contains one image, `flash.bin`, which is a build of U-Boot for the MaaXBoard.
