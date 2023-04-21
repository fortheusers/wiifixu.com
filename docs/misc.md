# Miscellaneous Issues

There are a few different types of problems that can occur on the Wii U, and have the same symptoms, and this page goes over different possibilities, in order from least to most severe.

## Possible issue: Bad system.xml
This is a very similar error to a bad coldboot install, and can be fixed in a similar manner to CBHC bricks, and can happen when messing with system files. In this case, you could try UDPIH and see if fixing the boot title fixes your system:

#### [➡️ Fixing Coldboot Haxchi Bricks](cbhc-brick/index.md)

## Possible issue: Corrupt files on NAND
If some crucial system ares are corrupt on NAND, they can be restored using [UDPIH](https://github.com/GaryOderNichts/udpih) and the [recovery_menu](https://github.com/GaryOderNichts/recovery_menu).

## Possible issue: Corrupt NAND
If the actual NAND filesystem has been corrupted, then restoring a file is not enough to fix it. If you have a NAND backup, you may be able to restore it via UDPIH, however this has to have had been made in advanced using homebrew software, otherwise it is not an option.

With no backup, in the future, you will be able to use [shinyquagsire's de_Fuse](https://douevenknow.us/post/714056575412764672/defuse-the-one-true-pwn), and a hard mod, to fix your console! As of the time of writing, this is not yet an option.

## Possible issue: Dead NAND
Certain revisions of the Wii U are using "Hynix" brand system memory. These have been observed to be unreliable and may start to "die".

Check your serial number against the list of consoles that have been submitted at the [Wii U System Database](https://wiiu.gerbilsoft.com), to see if it's likely you have a Hynix one.

If you do, there is a hardmod that can replace your system NAND with an SD card. You may be able to get a local electronics store to assist you in installing this, or watch some tutorials on how to do it on your own.

Information about the modchip by [Voultar is available here](https://twitter.com/Voultar/status/1646245011564945411).

**Notice:** This page is incomplete. If you would like to contribute, please [PR the project on Github](https://github.com/fortheusers/wiifixu.com).