# maaxboard-prebuilt
This repository contains prebuilt images for running seL4 on the Avnet MaaXBoard

## disk_images
This folder contains two disk images which can be written to an SD card:
  - `maaxboard-sel4-test.img.zip` - Contains U-Boot and a BOOT partition containing the seL4 test app for the MaaXBoard.
  - `maaxboard-uboot.img.zip` - Contains U-Boot, a BOOT partition for storing seL4 applications, and a FILESYSTEM partition.

## u-boot
This folder contains one image, `flash.bin` , which is a build of U-Boot for the MaaXBoard
