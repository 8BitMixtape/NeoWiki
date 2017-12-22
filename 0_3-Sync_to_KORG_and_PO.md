## Sync to KORG and Pocket Operators

Finally managed to test and connect to the KORG volca series and PO. Success!!!

Since the beginning of our hardware developement we have foreseen to ability to connect to other popular synthesizers, both with a CV output and input, aswell as synchronizing the speed/clock of connected devices with the "SYNC" out from the 8Bit Mixtape NEO.

https://github.com/8BitMixtape/Workshop_Examples/raw/master/NEO_062_Sequencer_syncOut-PO/NEO_062_Sequencer_syncOut-PO.ino.wav

This code needs "Reset disabled" set via fusebits
   `avrdude -P /dev/ttyACM0 -b 19200 -c avrisp -p t85 -U efuse:w:0xfe:m -U hfuse:w:0x5d:m -U lfuse:w:0xe1:m`

## How to sync to KORG volca series

![](images/mixtape_2_KORG_overview.jpg)

http://www.korg.com/us/products/dj/volca_beats/

The KORG sync input is usually connected with a mono-jack cable, so the sync signal has to be on the tip of the mini-jack. The 8Bit Mixtape was designed to send sync on the Ring [T|R|S] of the jack. To connect the 8Bit Mixtape as "Master" to the KORG we advise to use the outputs on the side and make your own connector cable.

Another method is to solder the plug of the 8Bit Mixtape inverted from the top of the PCB, which will switch the polarity of the connection!


## How to sync to pocket operator PO-series by Teenage Engineering

![](images/mixtape_2_PO_overview.jpg)

https://teenage.engineering/products/po