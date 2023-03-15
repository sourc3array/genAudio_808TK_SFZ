# genAudio - 808 Tape Kit (SFZ)

The **808 Tape Kit** is a virtual drum kit instrument in the open-standard [SFZ file format](https://sfzformat.com/) that utilizes the free [**808 Tape**](https://www.wavealchemy.co.uk/product/808-tape/) sample library from [*Wave Alchemy*](https://www.wavealchemy.co.uk/).


1.  808 Tape Kit Overview
2.  Compatibility
3.  Installation
4.  808 Tape Kit Overview
5.  Controls
    - Continuous Controllers
6.  Customization
7.  MIDI Reference
    - Key Note Mapping
    - CC IDs
8.  Getting Help
9.  Getting Involved
10.  Open Source Licensing Info
11.  Credits
12.  References


## Compatibility

The **808 Tape Kit** is designed for use with all SFZ-compliant sample players and audio plug-ins.

## Installation

1.  Download the free **808 Tape** sample library from *Wave Alchemy*:

    https://www.wavealchemy.co.uk/product/808-tape/

2.  Open the 'genAudio_808TapeKit' folder and populate the empty 'Samples' folder with the sample files located in the 'wa_808_tape' folder from *Wave Alchemy*.

3.  Load the instrument file 'genAudio_808TK.sfz' into your SFZ plug-in or stand-alone player.

## 808 Tape Kit Overview

The **808 Tape Kit** features sixteen (16) individual sound pads optimized for use with 4x4 MIDI pad controller layouts and finger drumming:

  - **DRUMS**: Kick (Sub), Kick, Low Tom and High Tom
  - **SNARES**: Snare, Snare (Alt), Rim and Clap
  - **HI-HATS**: Closed Hat, Closed Hat (Alt), Mid Hat and Open Hat
  - **CYMBALS**: Crash and Crash (Alt)
  - **PERCUSSION**: Clave and Maracas (FX)

All pads feature a Master Volume (V) control. 
All cymbals implement muting for enhanced realism and playability.

## Controls

The **808 Tape Kit** provides controls for:

  - (V) **Volume**: Sets the volume for each individual pad
  - (T) **Tight**: Varies the openness of the Mid Hat

### Continuous Controllers

Controls are linked to MIDI CCs for automation in DAWs, linking to hardware MIDI controllers, live performance, etc. See the *MIDI Reference* section below for a complete list of CC IDs and their assignments.

## Customization

TBD

## MIDI Reference

### Key Note Mapping

  - 35 - Kick (K1)
  - 36 - Kick (K2)
  - 41 - Low Tom (T1)
  - 43 - High Tom (T2)

  - 38 - Snare (S1)
  - 40 - Snare (S2)
  - 37 - Rim (A1)
  - 39 - Clap (A2)

  - 42 - Closed Hat (H1)
  - 44 - Closed Hat ALT (H2)
  - 45 - Mi(V) d Hat (H3)
  - 47 - Open Hat (H4)     

  - 48 - Crash (C1)
  - 50 - Crash (C2)
  - 46 - Clave (P1)
  - 49 - Maracas (P2)

### Continuous Controller IDs

  - 35 - (V) Kick-SUB
  - 36 - (V) Kick
  - 41 - (V) Low Tom
  - 43 - (V) High Tom

  - 38 - (V) Snare
  - 40 - (V) Snare-ALT
  - 37 - (V) Rim
  - 39 - (V) Clap

  - 42 - (V) Closed Hat
  - 44 - (V) Closed Hat (ALT)
  - 45 - (V) Mid Hat
  - 47 - (V) Open Hat     

  - 48 - (V) Crash
  - 50 - (V) Crash (ALT)
  - 46 - (V) Clave
  - 49 - (V) Maracas (FX)

## Getting Help

If you have any questions, concerns, bug reports, etc., please file an issue in this repository's Issue Tracker.

## Getting Involved

[Contribute](CONTRIBUTING.md) to this project with constructive feedback and feature requests.


----

### Open Source Licensing Info

1. [TERMS](TERMS.md)
2. [LICENSE](LICENSE)


----

### Credits

1. SFZ programming and sound design by [SOURC3ARRAY](https://soundcloud.com/sourc3array).

### References

1. [808 Tape](https://www.wavealchemy.co.uk/product/808-tape/) is a free collection of TR-808 drum machine samples recorded directly to 1/4″ analogue tape.
2. [sforzando](https://www.plogue.com/products/sforzando.html) is a free, SFZ 2.0 compliant sample player.
2. [SFZFormat](https://sfzformat.com/) provides an overview and reference for the SFZ file format.
3. [Wave Alchemy](https://www.wavealchemy.co.uk/) makes award-winning virtual instruments, samples and FX.
