Raspberry Pi Advance GBA BIOS Dumper

## Description
GBA BIOS dumper for Raspberry Pi Advance expantion board (https://cubic-style.jp/rpa_exp/).

## command log

$ gcc biosdump.c -lwiringPi -o biosdump
$ sudo ./biosdump

Waiting for GBA...
Sending header.
Getting encryption and crc seeds.
Seeds: ca, ec, ffffbbd1
Sending...
Waiting for checksum...
Gba: 41da, Cal: 41da
Boot Done.
connect start...
connect success!
recieve start...
.
.
.
.
recive finish!

## Author
CUBIC STYLE Sep 19, 2018




original program:
-----------------------------------------------------------------------------
Raspberry Pi GBA Loader - Rewrite version

## Description
This program is Rewrite version. https://github.com/akkera102/gba_01_multiboot 
and forked. https://github.com/MerryMage/gba-multiboot


## command log
$ gcc multiboot.c -lwiringPi -o multiboot
$ ./multiboot 2048.gba

Waiting for GBA...
Sending header.
Getting encryption and crc seeds.
Seeds: d0, 27, ffffc1d1
Sending...
Waiting for checksum...
Gba: 7113, Cal: 7113
Done.


## Author
MerryMage Aug  4, 2017(teensy version)
akkera102 Sep 17, 2018(raspberry pi version)


## License
CC0


