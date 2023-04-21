# UDPIH via Raspberry Pi Pico
- Download the latest `udpih.uf2` from the [releases page](https://github.com/GaryOderNichts/udpih/releases).
- Hold down the `BOOTSEL` button on the board and connect the Pico to your PC.  
  Your PC will detect the Pi as a storage device.
- Copy the `.uf2` file to the Pico. It will disconnect after a few seconds.

The Pico is now flashed and can be used for udpih. You can now follow the below instructions:

#### [➡️ Booting the recovery_menu](recovery-menu.md).

## Credits
USB Descriptor Parsing Is Hard (UDPIH) is by GaryOderNichts, and the write-up on how it works [can be found here](https://garyodernichts.blogspot.com/2022/06/exploiting-wii-us-usb-descriptor-parsing.html).

These instructions are modified from the [udpih](https://github.com/GaryOderNichts/udpih#instructions) project page.