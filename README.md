# Rust no_std NXP SC16IS752 SPI driver

## Attention

This is a fork from [rand12345's sc16is752](https://github.com/rand12345/sc16is752). Thanks for that!

The difference:
* Fixed interrupt handling
* Added support cycle read and write for **SPI** (I2C currently only stubbed)

Visit my other repo to see usage for it: [c3-ru-mamu](https://github.com/arnegue/c3-ru-mamu)

## Dual UART and 8x GPIO port expander

AKA:

* Waveshare Serial Expansion HAT
* MCU-752
* Isolated 485 HAT
* Raspberry Pi UART Expander

[Datasheet](https://www.nxp.com/docs/en/data-sheet/SC16IS752_SC16IS762.pdf)
