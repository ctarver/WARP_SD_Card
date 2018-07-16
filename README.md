# WARP SD Card
This is the files and bash script that will format an SD card to the way I like it for WARP boards

Note: I made this to run on my Linux laptop. My SD card always goes to sdb. If yours doesn't, edit the script!

## What's in each slot
Each slot has a different image for the WARP verision 3 board. They are as follows:

Slot | Content | Version | Radios |
--- | --- | --- | --- |
Slot 0 | WARPLab | 7.7.1 | 2 radio |
Slot 1 | WARPLab | 7.7.1 | 4 radio |
Slot 2 | 802.11 AP ref design | 1.4 | |
Slot 3 | WURCLab |  | |
Slot 4 | Calibration| | |

## Selecting the slot on the board
There are four switches on the v3 board on the upper right hand side. They are labeled 1,2,3,4.  1 is used to select SPI Flash configuration. If 1 is down, the other switches select the slot on the SD card in binary with 4 representing the LSB bit and 2 representing the MSB.
