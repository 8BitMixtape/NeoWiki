# TinyAudioBoot

Attiny85 version of [Audioboot](http://www.hobby-roboter.de/forum/viewtopic.php?f=4&t=127) enhanced with EEPROM write mode. 

## Source code

* Budi Prakosa Repo
* Chris Haberer Repo

## Changelog

- todo

## Features

- Small bootloader size
- EEPROM write mode for setting variables without reprogram the board
- Webinterface with [Hex2WavJS](4_4.1-Hex2Wav.md), EEPROM write
- Cross platform [Hex2Wav](4_4.1-Hex2Wav.md) command line interface

## Issues

* Binary compiled with 32 Bit debian todo add 64/32
* Missing libasound: 
    * ERROR: /0.0.15/tools/hex2wav/linux/hex2wav_bin: No such file or directory
NEO_022_FamilyMart.ino.wav: No such file or directory
Error compiling.
    * apt-get install libasound2-plugins:i386

## Projects using TinyAudioBoot

- 8BitMixtape NEO
- [Synsonique Drum](https://janostman.wordpress.com/2017/07/10/synsonique-drum/) 

## Credits

* [Budi Prakosa](http://manticore.id) (initial TinyAudioBoot Attiny85, Hex2Wav/JS)
* [Chris Micro](https://github.com/ChrisMicro) (original AudioBoot code, further TinyAudioBoot enhancement)
* [Fredrik Olofsson](http://fredrikolofsson.com/) (HexParser code in javascript)