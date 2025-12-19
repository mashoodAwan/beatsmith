# BeatSmith DAW - User Guide

A browser-based beat making application for creating drum patterns and arrangements.

---

## What is a DAW?

**DAW** stands for **Digital Audio Workstation**. It's software used to create, edit, and produce music on a computer. Think of it as a digital music studio in your browser.

---

## Interface Overview

### Transport Controls (Play/Stop)

| Button | Function |
|--------|----------|
| ▶ | Play your beat |
| ■ | Stop playback |

**Keyboard Shortcut:** Press `Spacebar` to play/stop.

---

## Key Parameters

### BPM (Beats Per Minute)

BPM controls the **speed** of your music.

| BPM Range | Feel | Music Examples |
|-----------|------|----------------|
| 70-90 | Slow, chill | Hip-hop, R&B ballads |
| 100-120 | Medium, groovy | Pop, house music |
| 128 | Club/dance standard | EDM, techno |
| 140-170 | Fast, energetic | Drum & bass, dubstep |

> **Rule:** Higher BPM = Faster music

---

### Swing %

Swing adds a **human, groovy feel** to your beat.

**0% Swing**
- Perfectly robotic timing
- Every hit lands exactly on the grid
- Sounds mechanical, like a machine

**20-50% Swing**
- Notes are slightly delayed in alternating pattern
- Creates a "bounce" or "shuffle" feel
- Sounds more natural and groovy

**Analogy:** Think of walking.
- 0% swing = Military march (LEFT-RIGHT-LEFT-RIGHT)
- With swing = Relaxed stroll (LEFT---right-LEFT---right)

---

### PAN (Panning)

Panning controls where sound sits between your **left and right speakers/headphones**.

| Value | Position |
|-------|----------|
| -1 | Full left speaker only |
| -0.5 | Mostly left |
| 0 | Center (both speakers equal) |
| +0.5 | Mostly right |
| +1 | Full right speaker only |

**Why use panning?**
- Creates **width** and **space** in your mix
- If everything is at 0 (center), the mix sounds flat
- Spreading sounds left/right makes music feel more alive and immersive

---

### DB (Decibels) - Volume

Controls how **loud** each individual sound is.

| Value | Meaning |
|-------|---------|
| +6 | Much louder |
| +2 | Slightly louder |
| 0 | Default/normal volume |
| -2 | Slightly quieter |
| -6 | Much quieter |
| -20 | Very quiet |

> **Tip:** Use negative values to turn down sounds that are too loud. This helps balance your mix.

---

## The Step Grid (Sequencer)

The main grid where you **program your beat**.

### How It Works

```
Rows    = Different sounds (kick, snare, hi-hat, etc.)
Columns = Moments in time (called "steps")
16 steps = 1 bar of music (the pattern loops)
```

### Visual Guide

| Box Color | Meaning |
|-----------|---------|
| Orange | Sound plays at this step |
| Dark gray | Silence (no sound) |

### Beat Markers (1, 2, 3, 4)

The numbers at the top represent the **main beats** - these are the moments when you'd count "1, 2, 3, 4" along with the music.

Each beat contains 4 steps (called 16th notes), giving you 16 steps total per bar.

---

## Sound Library

### Available Sounds

| Sound | Description | Typical Use |
|-------|-------------|-------------|
| **Kick 808** | Deep "boom" bass drum | The heartbeat of the track, usually on beats 1 and 3 |
| **Snare Hard** | Sharp "crack" sound | Usually on beats 2 and 4 (the backbeat) |
| **Hat Closed** | Short metallic "tick" | Adds rhythm, often on every step or every other step |
| **Hat Open** | Longer "tsssss" cymbal | Creates movement, often before beat changes |
| **Clap** | Hands clapping sound | Often layered with snare for emphasis |
| **Perc Click** | Short percussive accent | Adds extra rhythm and interest |
| **Bass 808** | Low bass note | Adds weight and groove to the track |

---

## Track Controls

### Mute (M Button)

- **Function:** Silences that sound completely
- **Use case:** Hear how the beat sounds without one element
- **Visual:** Button turns orange when active

### Solo (S Button)

- **Function:** Plays ONLY that sound, mutes everything else
- **Use case:** Focus on one sound in isolation
- **Visual:** Button turns green when active

> **Tip:** You can solo multiple tracks at once to hear just those sounds together.

---

## Pattern Bank

Patterns are different **sections** of your song. Each pattern has its own step grid.

### Default Patterns

| Pattern | Typical Use |
|---------|-------------|
| **Intro** | Beginning of song - usually simpler, builds anticipation |
| **Main Loop** | The core beat that repeats through most of the song |
| **Breakdown** | Quieter section - stripped down, creates contrast |
| **Outro** | Ending section - often fades out or simplifies |

### How to Use

1. Click a pattern name to select it
2. The step grid updates to show that pattern
3. Edit the steps as needed
4. Selected pattern shows with orange background

---

## Song Arrangement (Timeline)

The timeline determines the **order** your patterns play in Song mode.

### Example Arrangement

```
Intro → Main Loop → Main Loop → Breakdown → Main Loop → Outro
```

This plays:
1. Intro pattern (once)
2. Main Loop pattern (twice)
3. Breakdown pattern (once)
4. Main Loop pattern (once)
5. Outro pattern (once)

### Timeline Controls

| Action | How To |
|--------|--------|
| Add pattern | Click the `+` button |
| Change pattern | Click on existing slot |
| Remove pattern | Hover over slot, click `×` |
| Clear all | Click `CLEAR SONG` button |

---

## Play Modes

### PATTERN Mode (Orange Button)

- Loops only the currently selected pattern
- Repeats forever until you stop
- Great for creating and editing individual patterns

### SONG Mode (Green Button)

- Plays through your entire arrangement
- Goes from first to last pattern in timeline
- Loops back to beginning after finishing

> Click the play mode button to toggle between modes.

---

## Exporting Your Beat

### Export .WAV

Creates a downloadable audio file of your beat.

**Settings:**
- **LENGTH(S):** How many seconds to export (default: 30)

**Steps:**
1. Set your desired length in seconds
2. Choose play mode (Pattern or Song)
3. Click `EXPORT .WAV`
4. Wait for rendering
5. File downloads automatically

**Output:** Standard WAV audio file that works with any music player or video editor.

---

## Quick Start Guide

### Making Your First Beat

1. **Set your tempo** - Try 128 BPM for a dance beat or 90 BPM for hip-hop

2. **Add a kick drum** - Click steps 1, 5, 9, 13 on the Kick row (this puts kicks on every beat)

3. **Add snare** - Click steps 5 and 13 on the Snare row (beats 2 and 4)

4. **Add hi-hats** - Click every other step on Hat Closed for a basic rhythm

5. **Press play** - Hit spacebar or click ▶ to hear your beat

6. **Experiment** - Add more sounds, try different patterns, adjust volume and panning

---

## Tips for Better Beats

### Volume Balance
- Keep kick and snare prominent
- Hi-hats should be quieter (-4 to -6 dB)
- Bass should be felt, not overpowering

### Panning Suggestions
- Keep kick, snare, and bass in the CENTER (0)
- Pan hi-hats slightly left or right (-0.2 to +0.2)
- Pan percussion elements wider for space

### Swing
- Start with 0% to learn, then add 15-25% for groove
- Higher swing (40-50%) for jazz or shuffle feels

### Pattern Variation
- Don't make every pattern the same
- Remove elements in breakdowns
- Add extra hits in main loops for energy

---

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `Spacebar` | Play / Stop |

---

## Technical Requirements

- Modern web browser (Chrome, Firefox, Edge, Safari)
- Audio output (speakers or headphones)
- No installation required - runs entirely in browser

---

## Glossary

| Term | Definition |
|------|------------|
| **Bar** | A musical unit containing a set number of beats (usually 4) |
| **Beat** | The basic unit of time in music - what you tap your foot to |
| **Step** | A subdivision of a beat (16 steps = 4 beats = 1 bar) |
| **Loop** | A section of music that repeats |
| **Mix** | The balance of all sounds together |
| **16th Note** | Each individual step in the sequencer |
| **Backbeat** | Emphasis on beats 2 and 4 (where snare usually hits) |

---

*Made with BeatSmith - Browser-based beat making for everyone.*
https://mashoodawan.github.io/beatsmith/
