The original readme file is located [here](README_original).

<hr>

# ROCK64 U-Boot
This fork of [ayufan's ROCK64 U-Boot](https://github.com/ayufan-rock64/linux-u-boot) aims at fixing stability issues that some users have when memory is clocked too high[^1][^2], while retaining extra features over stock bootloader.

## Flashing
The flashing procedure is the same as described on [ayufan's guide](https://github.com/ayufan-rock64/linux-build/blob/master/recipes/flash-spi.md). The only thing changing is (obviously) the image, you can download the latest one [here](https://github.com/marcovolpato00/rock64-u-boot/releases/latest) or build your own.

## Building
*TODO*

[^1]: [https://forum.armbian.com/topic/15082-rock64-focal-fossa-memory-frequency/](https://forum.armbian.com/topic/15082-rock64-focal-fossa-memory-frequency/)
[^2]: [https://forum.pine64.org/showthread.php?tid=11209](https://forum.pine64.org/showthread.php?tid=11209)