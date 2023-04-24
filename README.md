# 808TK (SFZ)

The **808TK** is a virtual drum kit instrument created by [GEN Audio]( https://genaudio.biz ) for the open-standard [SFZ]( https://sfzformat.com/ )  file format that utilizes the free [**808 Tape**](https://www.wavealchemy.co.uk/product/808-tape/) sample library from [*Wave Alchemy*](https://www.wavealchemy.co.uk/).

***

1.  Compatibility
2.  Installation
3.  808TK Overview
4.  Controls
    - Continuous Controllers (CCs)
5.  MIDI Reference
    - Key Note Mapping
    - CC IDs
6.  Getting Help
7.  Getting Involved
8.  Open Source Licensing Info
9.  Credits
10.  References

***

## Compatibility

The **808TK** is designed for use with SFZ sample players and audio plug-ins.

***

## Installation

1.  Download the free **808 Tape** sample library from *Wave Alchemy*:

    https://www.wavealchemy.co.uk/product/808-tape/
    
2.  Download the 808TK (SFZ) software package:

    https://github.com/sourc3array/genAudio_808TK_SFZ

3.  Extract the ZIP file archive and move the '808TK_SFZ' folder into your SFZ instruments folder.

2.  Open the '808TK_SFZ' folder and populate the empty 'Samples' folder with the sample files located in the 'wa_808_tape' folder from *Wave Alchemy*.

3.  Load the instrument file '808TK.sfz' into your SFZ plug-in or stand-alone player.

***

## 808TK Overview

The **808TK** features fifty-three (53) 24-bit drum samples layered over sixteen (16) individual sound pads. The sound bank has been curated for optimal use with 4x4 drum pad controllers and finger drumming:

  - **DRUMS**: Kick (Sub), Kick, Low Tom and High Tom
  - **SNARES**: Snare, Snare (Alt), Rim and Clap
  - **HI-HATS**: Closed Hat, Closed Hat (Alt), Mid Hat and Open Hat
  - **CYMBALS**: Crash and Crash (Alt)
  - **PERCUSSION**: Clave and Maracas (FX)

Each drum pad contains multiple velocity layers to provide clean, saturated and driven variations for each sound. Multiple velocity layers provide a range of  satuation levels using [non-linear velocity mappings]( https://genaudio.biz/sonic-curve/ ) that accurately capture the nuances of human playing. Several pads feature additional sample layers and sound design nuances, giving the **808TK** its unique sonic texture. All pads feature an independent Volume control, with an additional Tight control for the hi-hats. Muting has been implemented for each cymbal for enhanced realism and playability.

***

## Controls

The **808TK** provides controls for:

  - (V) **Volume**: Sets the volume for each individual pad
  - (T) **Tight**: Varies the openness of the Mid Hat

### Continuous Controllers

Controls are assigned to MIDI CCs for automation in DAWs, linking to hardware MIDI controllers, live performance, etc. See the [Continuous Controller IDs](#continuous-controller-ids) section below for a complete list of CC IDs and their assignments.

***

## MIDI Reference

### Key Note Mapping

Default MIDI numbers and note names for the **808TK**:

  - 35 - Kick (SUB) -- B2
  - 36 - Kick -- C1
  - 41 - Low Tom -- F1
  - 43 - High Tom -- G1

  - 38 - Snare -- D1
  - 40 - Snare (ALT) -- E1
  - 37 - Rim -- C#1
  - 39 - Clap -- D#1

  - 42 - Closed Hat -- F#1
  - 44 - Closed Hat (ALT) -- G#1
  - 45 - Mid Hat -- A1
  - 47 - Open Hat -- B1

  - 48 - Crash -- C2
  - 50 - Crash (ALT) -- D2
  - 46 - Clave -- A#1
  - 49 - Maracas (FX) -- C#2

### Continuous Controller IDs

The (T) Tight control for the Mid Hat is assigned to the MIDI default for *Foot Pedals*.

The default CC assignments for all (V) Volume controls correspond to *Undefined* channels in the MIDI specification to minimize potential comflicts in typical MIDI setups.

  - 04 - (T) Tight
  
  - 14 - (V) Kick (SUB)
  - 15 - (V) Kick
  - 20 - (V) Low Tom
  - 21 - (V) High Tom

  - 22 - (V) Snare
  - 23 - (V) Snare (ALT)
  - 24 - (V) Rim
  - 25 - (V) Clap

  - 26 - (V) Closed Hat
  - 27 - (V) Closed Hat (ALT)
  - 28 - (V) Mid Hat
  - 29 - (V) Open Hat     

  - 30 - (V) Crash
  - 31 - (V) Crash (ALT)
  - 85 - (V) Clave
  - 86 - (V) Maracas (FX)

***

## Getting Help

If you have any questions, concerns, bug reports, etc., please file an issue in this repository's *Issue Tracker*.

***

## Getting Involved

Contribute to the **808 Tape Kit (SFZ)** with your constructive feedback.

***

### Open Source Licensing Info

2. [LICENSE](LICENSE)

***

### Credits

1. SFZ programming and sound design by [SOURC3ARRAY]( mailto:sourc3array@genaudio.biz ).

***

### References

1. [GEN Audio]( https://genaudio.biz ): Precision instruments, virtual instrument kits and tutorials for Decent Sampler · Free & Open Source
2. [808 Tape]( https://www.wavealchemy.co.uk/product/808-tape/ ): Free collection of TR-808 drum machine samples recorded directly to 1/4″ analogue tape.
3. [Wave Alchemy]( https://www.wavealchemy.co.uk/ ): Makers of award-winning virtual instruments, samples and FX.
2. [sforzando]( https://www.plogue.com/products/sforzando.html ): A free, SFZ 2.0 compliant sample player.
2. [SFZFormat]( https://sfzformat.com/ ): An overview and reference for the SFZ file format.
