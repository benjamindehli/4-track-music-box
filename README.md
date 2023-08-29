# 4-track Music Box - Version: [1.1]

Date: 2023-08-29

Name: Benjamin Dehli

Profile: [pianobook.co.uk/profile/benjamindehli](https://www.pianobook.co.uk/profile/benjamindehli/)

## Included formats

- Decent Sampler

## Release notes

### Version 1.1

- Fixed typo (wrong casing) in the directory name for some samples, which caused the samples not to load on some devices.
- Added a "split" preset to play samples at normal speed and samples at half speed in different parts of the keyboard.

## Description

A music box recorded on to cassette tape and played back at half speed and normal/original speed. Playing back at half speed results in an octave lower pitch.

## Technical specification

|                       | Sample rate | Bit depth | Channels   | Number of files | File size |
|----------------------:|------------:|----------:|------------|----------------:|----------:|
|           **Samples** |      48 kHz |    24 bit | 1 (mono)   |              52 |  50.40 MB |
| **Impulse responses** |      48 kHz |    24 bit | 2 (stereo) |               4 |   3.60 MB |

## User Interface

|![Overview](/Screenshots/4-track-music-box.png)|
|:--:|
|Overview|

### Instrument

|![Button controls for the instrument settings](/Screenshots/instrument.png)|
|:--:|
|Button controls for the instrument settings|

#### Velocity and damping

- Velocity
  - Determines whether the velocity should affect the volume of the samples
- Damping
  - When damping is off, the sample will continue to play after you release the key (like a music box)
  - When damping is on, the sample will fade out quickly after you release the key

### Mixer

|![LFO controls](/Screenshots/mixer.png)|
|:--:|
|Mixer controls|

#### Volume

Mix between the normal speed samples and the half speed samples. They also have independent tremolo controls.

#### Tremolo

The **tremolo rate** and **tremolo depth** knobs enable you to modulate the amplitude of the sound with the desired depth and rate using a Low-Frequency Oscillator (LFO).

- Tremolo Rate
  - Tremolo rate determines the speed at which the modulation occurs
- Tremolo Depth
  - Adjust the Tremolo depth to introduce subtle or pronounced variations in volume

### Effects

These effects are achieved using carefully crafted impulse responses. The echo effect employs a Fulltone Tube Tape Echo recorded twice for stereo, while the reverb effect draws from a Chase Bliss Audio & Meris CXM 1978 reverb pedal with a room setting.

#### Echo

|![Controls for the tape echo impulse response](/Screenshots/echo.png)|
|:--:|
|Controls for the tape echo impulse response|

Select from two distinctive echo options: the short echo, delivering a classic slapback effect, and the long echo, characterized by a slower decay and numerous repeats.

- On
  - Turns the echo on and off
- Long
  - Switches between a short slapback echo and a long echo with slow repeats and high feedback
- Mix
  - Mix between direct signal and echo signal

#### Reverb

|![Controls for the room reverb impulse response](/Screenshots/reverb.png)|
|:--:|
|Controls for the room reverb impulse response|

You'll also find two reverb effects: the short reverb, evoking the intimacy of a small room, and the long reverb, enveloping your sound in the vastness of a spacious environment.

- On
  - Turns the reverb on and off
- Long
  - Switches between a short/small room reverb and a long/big room reverb
- Mix
  - Mix between direct signal and reverb signal

### Fidelity

|![Controls for the fidelity settings](/Screenshots/fidelity.png)|
|:--:|
|Controls for the fidelity settings|

#### Hi-fi

When the **hi-fi** switch is turned on, no effects are applied. When it's turned off, some filtering, saturation and modulation are added for a lo-fi effect. The saturation becomes more pronounced when you turn up the volume in the mixer section.

- Hi-fi
  - Turns the lo-fi effects on and off
