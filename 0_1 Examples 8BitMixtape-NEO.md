## 8Bit Mixtape NEO

See also [ChrisMicro's repository](https://github.com/ChrisMicro/AttinySound) with maaaany new codes.


### testComponents-Advanced

Test all the components of your hardware.

https://github.com/8BitMixtape/8Bit-Mixtape-NEO/raw/master/Code/NEO_000_testcomponents_advanced/NEO_000_testcomponents_advanced.ino.ino.wav

### 05092008_ChrisMicro_TraschMetalResearchGroup

A claasiic by ChrisMicro!! Sounds like a heavy metal guitar or Pulp Fictions soundtrack. 
* leftPot defines pitch, 
* rightPot how fast the guitar is plucked.  
* buttons do nothing. 
* sorry now LEDs, bro...

https://github.com/8BitMixtape/8Bit-Mixtape-NEO/raw/master/wavFiles/05092008_ChrisMicro_TraschMetalResearchGroup.wav


### NEO_8Pixel_oneliners

Algorithmic sounds, inspired by Viznut. Updated the classic OneLiners to the 8Bit Mixtape NEO, turn on/off visuals.

 `snd = t*((t>>12|t>>8)&63&t>>(p1>>3));`

* leftPot: changes something in the formula (p1, in example above)
* turn leftPot to left to toggle between analogWrite and digitalWrite
* right change sample speed
* buttonLeft: changing OneLiner
* buttonRight: Stop NEO-pixel Visuals (makes clearer sound)

https://github.com/8BitMixtape/8Bit-Mixtape-NEO/raw/master/Code/NEO_8Pixel-OneLiners/NEO_8Pixel-OneLiners.ino.wav

### IrqPcControlSynth 054

PC controlled synthesizer with two LFO and one HFO To control the synth you need this java application. Download Main_IrqPcControllerForSynth.jar

On windows just click on it to start it. On linux you can run it from command line:

```
java -jar ./Main_IrqPcControllerForSynth.jar
java -jar ~/Arduino/AttinySound/_053_IrqPcControlSynth/java/Main_IrqPcControllerForSynth.jar
```

https://github.com/8BitMixtape/8Bit-Mixtape-NEO/raw/master/Code/NEO_054_IrqPcControlSynth_usingNeoLib_colorGeeked/NEO_054_IrqPcControlSynth_usingNeoLib_colorGeeked.ino.wav

### NeoPixel Sequencer 061 dusjagrMod2
8 step sequencer with different waveforms by ChrisMicro.

Press both bottoms at the same time to start cycle. Updated sequencer, more colors, adjust envelope, smooth waveform selection

// progMode
* leftPot: waveform (changes color of stepLED)
* rightPot: frequency (hysteresis, don't move to keep previous value)
* buttonLeft: 1 step backward
* buttonRight: 1 step forward
* both Buttons: Start playMode

// playMode
* leftPot: duration of envelope
* rightPot: clock speed
* both Buttons: switch to progMode

https://github.com/8BitMixtape/8Bit-Mixtape-NEO/raw/master/Code/_061_8NeoPixelSequencer_dusjagrMod2/_061_8NeoPixelSequencer_dusjagrMod2.ino.wav

### NeoPixel Sequencer 062 with Sync-Out

See [here](/0_3-Sync_to_KORG_and_PO.md "here")

### MiniSynthWithNeoPixels_Coco
A nice little synth noisy toy. We should add more settings to it.

* rightButton: toggle to always ON, and switch to next setting
* leftButton: trigger tone once and start ADSR.
* pots do various things that I will never understand....

Updated the synth (12), for cooler LED effects and other stuff

https://github.com/8BitMixtape/Neocococat/raw/master/code/02.%20synths/_012_miniSynthWithNeoPixels_Coco_updated/_012_miniSynthWithNeoPixels_Coco_updated.ino.wav

### Family Mart Chime

Because we can... Greetings from Taipei!

* Press rightButton to start playing the "song"

https://github.com/8BitMixtape/8Bit-Mixtape-NEO/raw/master/Code/NEO_022_FamilyMart/NEO_022_FamilyMart.ino.wav

### One Pixel Board

Ada_1Pixel_oneliners

https://github.com/8BitMixtape/8Bit-Mixtape-NEO/raw/master/Code/Ada_1Pixel_NEO-OneLiner/Ada_1Pixel_NEO-OneLiner.ino.wav

### (Attiny SoundPitix-VCO NEO)

Outdated, but here due to historic reasons. A simple VCO, slightly outdated software syhnth, but cool with visuals now. Board needs to be restarted again after upload to work properly.

https://github.com/8BitMixtape/8Bit-Mixtape-NEO/raw/master/Code/_003_soundPittix_NEO-Buttons/_003_soundPittix_NEO-Buttons.ino.wav

### Gär Lämpli - ギャランプリー - 起酵燈仔

Gär Lämpli - ギャランプリー

https://github.com/8BitMixtape/8Bit-Mixtape-NEO/raw/master/boards/NEO-Coconut/DS18x20_Temperature_Hamamatsu_chistli/DS18x20_Temperature_Hamamatsu_chistli.ino.wav