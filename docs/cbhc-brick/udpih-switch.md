# UDPIH via Nintendo Switch Payload

This is a payload to run [UDPIH](https://github.com/GaryOderNichts/udpih) using a hacked Nintendo Switch.

## Instructions

- Download the latest `udpih_nxpayload.bin` from the [Github releases page](https://github.com/GaryOderNichts/udpih_nxpayload/releases) and inject it using a payload injector.
    - For instance, [switch.exploit.fortheusers.org](https://switch.exploit.fortheusers.org), or [TegraRcmSmash](https://switchtools.sshnuke.net/).
    - View more info on sending a payload on the [NH Switch Guide](https://nh-server.github.io/switch-guide/user_guide/emummc/sending_payload/)
- Start the gadget by selecting `Run UDPIH gadget` using the `POWER` button.

You can now follow the below instructions:

#### [➡️ Booting the recovery_menu](recovery-menu.md).

## Credits
USB Descriptor Parsing Is Hard (UDPIH) is by GaryOderNichts, and the write-up on how it works [can be found here](https://garyodernichts.blogspot.com/2022/06/exploiting-wii-us-usb-descriptor-parsing.html).

This payload is a heavily stripped down version of [hekate](https://github.com/CTCaer/hekate) with support for the udpih gadget, so all credits for the NX payload go to [@CTCaer](https://github.com/CTCaer/hekate) and all other hekate contributors.

These instructions are modified from the [udpih_nxpayload](https://github.com/GaryOderNichts/udpih_nxpayload#instructions) project.