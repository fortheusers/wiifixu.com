### Booting the recovery_menu

> ⚠️ Important notes for this to work:
> - Make sure **no** other USB Devices are attached to the console.
> - Only use USB ports on the front of the console, the back ports **will not** work.
> - If your console has standby mode enabled, pull the power plug and turn it on from a full coldboot state.

- Copy the latest release of the [recovery_menu](https://github.com/GaryOderNichts/recovery_menu/releases) to the root of your FAT32 formatted SD Card.
- Insert the SD Card into the console and power it on.
- As soon as you see the "Wii U" logo on the TV or Gamepad plug in your Zero/Pico.  
    - This timing is important. If you're already in the menu, the exploit won't work..
- After a few seconds you should be in the recovery menu.

Check out the [recovery_menu README](https://github.com/GaryOderNichts/recovery_menu) for more information about this menu.

To restore functionality, choose "Set Coldboot Title" by pressing the POWER button to choose the first option.

From here, choose one of the following options, depending on the region of your Wii U:

> Wii U Menu (JPN) - 00050010-10040000
> Wii U Menu (USA) - 00050010-10040100
> Wii U Menu (EUR) - 00050010-10040200

After setting the title, reboot the Wii U and the error message should go away!

If it didn't, try describing your issue on the [NH Discord Server](https://discord.gg/C29hYvh).

# Credits
USB Descriptor Parsing Is Hard (UDPIH) is by GaryOderNichts, and the write-up on how it works [can be found here](https://garyodernichts.blogspot.com/2022/06/exploiting-wii-us-usb-descriptor-parsing.html).

These instructions are modified from the [udpih](https://github.com/GaryOderNichts/udpih#instructions) project page.