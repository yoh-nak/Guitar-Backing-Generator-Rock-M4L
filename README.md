# Guitar Backing Generator Rock v2.0

**Guitar Backing Generator Rock** is a Max for Live MIDI effect for creating rock-oriented guitar backing parts, driving chord strums, riffs, arpeggios, and hybrid accompaniment in Ableton Live.

Version 2.0 is rebuilt on the newer Guitar Backing Generator v2.0 engine, with **2,600 presets across 52 rock styles**. It emphasizes powerful, energetic performances while retaining cutting, brushing, muted strokes, and more subtle accompaniment techniques.

This is a **MIDI generator, not a guitar instrument**. Place it **before a guitar instrument** on a MIDI track and use your preferred VST, Kontakt library, or other MIDI-compatible sound source.

## Main Features

- **2,600 rock-focused presets**: 52 styles, 50 presets per style
- Three performance modes: **BACKING**, **ARPEGGIO**, and **HYBRID**
- Hard 8th- and 16th-note strumming, driving downstrokes, and alternate strokes
- Power-chord riffs, gallops, syncopated accents, stop-start phrases, and breakdowns
- Palm-muted chugs, open-chord transitions, cutting, brushing, and rhythmic variation
- Verse, chorus, intro, pre-chorus, bridge, fill, and outro-oriented patterns
- Adjustable picking, dynamics, gate, strum timing, damping, and humanization
- MIDI input from an existing **MIDI CLIP** or real-time **MIDI KEYBOARD** performance
- **RECORD**, **STOP**, **WRITE CLIP**, **NEW TAKE**, and **APPEND TAKE** workflows
- **EXPORT MIDI** for saving generated performances as a Standard MIDI File
- Time-signature control with **FOLLOW LIVE** and manual meter settings
- A single `.amxd` device; no genre-specific guitar instrument is required

## Rock Preset Library

The library is organized into five families:

| Family | Styles | Presets |
| --- | ---: | ---: |
| Roots / Classic | 11 | 550 |
| Alternative / Indie | 12 | 600 |
| Punk / Hardcore | 8 | 400 |
| Metal / Heavy | 13 | 650 |
| Prog / Melodic | 8 | 400 |
| **Total** | **52** | **2,600** |

Styles include Classic Rock, Blues Rock, Hard Rock, Grunge, Garage Rock, Indie Rock, Punk Rock, Pop Punk, Skate Punk, Post-Hardcore, J-Rock / Anison, Heavy Metal, Thrash / Speed, Metalcore, Death Metal, Doom Metal, Djent / Prog Metal, Progressive Rock, Math Rock, Power Ballad Rock, and more.

Examples of performance types:

- **STRUM / FURIOUS EIGHTHS** — relentless 8th-note chord strumming
- **STRUM / WALL SIXTEENTHS** — dense 16th-note strum patterns
- **CHORUS / BIG FULL STRUM** — open, full-chord chorus backing
- **RIFF / GALLOP** — fast, galloping rhythmic figures
- **RIFF / MUTE TO OPEN** — transitions between muted and open attacks
- **RIFF / SYNCOPATED POWER** — offbeat power-chord accents
- **RIFF / TWO BAR HOOK** — two-bar riff phrases
- **BREAKDOWN / HALF TIME** — heavier half-time rhythmic emphasis

Preset patterns and articulations differ by style; the device is not simply the same backing pattern with different names.

## Performance Controls

Along with the standard rhythm and performance controls, the Rock edition includes:

| Parameter | Function |
| --- | --- |
| **CHUG TIGHT %** | Adjusts the tightness and focus of low-register muted hits |
| **PICK ATTACK %** | Adjusts pick-attack emphasis and stroke dynamics |
| **BAR FILL %** | Adds rhythmic variation near the end of bars |
| **STRUM ms** | Sets the timing spread of notes within a stroke |
| **GATE ms / DAMP %** | Adjusts note length and muting behavior |
| **STROKE DYN %** | Changes the relative strength of down/up strokes |
| **HUMANIZE %** | Adds subtle timing and velocity variation |

Additional options control groove, swing, accents, voicing, bass movement, picking style, release, strum range, and variation.

## Basic Workflow

1. Add the `.amxd` device to a MIDI track **before** a guitar instrument.
2. Select **MIDI CLIP** or **MIDI KEYBOARD** as the input source.
3. Supply MIDI chords or notes from the chosen source.
4. Choose a preset family, rock style, and performance preset.
5. Adjust **BACKING**, **ARPEGGIO**, or **HYBRID** settings to fit your arrangement.
6. For live input, use **RECORD** and **STOP** to capture the generated performance.
7. Use the clip-writing / take controls or **EXPORT MIDI** to keep the result.

## Chord Voicing

The device normally works from the **MIDI chord voicing you provide**. It does not automatically turn every piano-style chord into a physically realistic guitar voicing.

Voicing options include **AS PLAYED** and **POWER FIFTH**, but for more deliberate guitar-style voicings, use **Chord Voicing Writer** before Guitar Backing Generator Rock. This gives you control over the chord shapes while the generator handles rhythmic performance.

## MIDI Notes and Controller Data

All **2,600 factory presets** have optional **Expression (CC11 / CC1)**, **Pitch Bend**, and **Aftertouch** generation **OFF by default**. These functions can be enabled manually. How a guitar instrument responds to MIDI controllers depends on that instrument.

**Important:** Ableton Live clip-writing functions in this device write **MIDI notes**. If you enable controller generation and need to preserve its CC, pitch-bend, or aftertouch events, use **EXPORT MIDI** instead. Exported MIDI can also include controller reset messages even when factory presets have expression disabled.

The device uses MIDI-based articulation rather than assuming any particular guitar library's proprietary keyswitch mapping. The final sound depends on your chosen guitar instrument, amp/effects, and input voicing.

## What's New in v2.0

- Rebuilt from the newer Guitar Backing Generator v2.0 engine
- Expanded to **52 rock styles and 2,600 presets**
- Added hard strumming, dense rhythmic riffs, chugs, gallops, and heavier transitions
- Preserved cutting, brushing, arpeggios, and hybrid accompaniment
- Introduced Rock-focused controls for chug tightness, pick attack, and bar-end fills
- Improved preset organization and simplified the device-view layout
- Retained MIDI recording, clip writing, take workflows, and MIDI export

## Installation

1. Download `Guitar_Backing_Generator_Rock_v2.0.amxd` from this repository.
2. Open Ableton Live with Max for Live support.
3. Drag the device onto a MIDI track, before your guitar instrument.
4. Select a preset and start playing or rendering chords.

## Modifications and Feedback

You are welcome to modify the device, edit its internal presets, and share modified versions **free of charge**. Please do not sell modified versions.

If a preset, playing style, or feature could be improved, feedback and suggestions are welcome.
