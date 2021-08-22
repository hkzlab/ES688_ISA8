# ES688F / OPL3 8bit ISA Sound Card

## Introduction

This is a sound card for the ISA 8bit bus sporting the **ES688F** chip by *ESS Technology* and the **YMF262** chip by *Yamaha*, also known as the **OPL3**.

This board provides selectable **Sound Blaster PRO** / **Sound Blaster** emulation and **OPL3** compatibility.

It's completely jumper-configurable, requiring no software except the *essvol* utility to set the volume.

![Rev. 1.1 Board](pics/rev_1.1_board.jpg)

This board provides the following connections:

* Speaker out (amplified)
* Line out
* Line in
* Aux in (internal header)
* Microphone in (internal header)
* Joystick port
* MIDI on Joystick port
* Volume regulation pot

### Disclaimer

I take NO responsibility for what happens if you decide to build and use this card. Your computer might crash, catch fire or be destroyed in other nasty ways.
You're encourauged to take what you deem fit from this, and use it in your projects!

### Functionalities

✅ means I tested the functionality and it works, ❌ means I tested the functionality and found issues, ? means that the functionality has yet to be tested.

* [✅] FM Synthesis via OPL3
* [✅] Digital audio playback
* ? Stereo (left/right channel) check (Tested with Sound Blaster PRO Test program, digitized sound mode)
* [✅] Joystick port
* [✅] Speaker Out (amplified)
* [?] Line out
* [?] Line in
* [?] AUX In
* [?] Microphone in
* [?] MIDI output via Joystick port

The card was tested on:

* [✅] NEC V20 9.5Mhz / DOS 6.22

## Configuration

This card is configured via jumpers.

**TODO**

## Bill of Materials

**TODO**

## Known Issues

### Rev 1.1

* Missing silkscreen to describe JP1

### Rev 1.0

* Wrong footprints for YAC512 and YMF262 chips
* Volume pot placed after audio decoupling. Wrong.

## Credits

Thanks to [Sergey Kiselev](https://github.com/skiselev) for his symbol/footprint library!

