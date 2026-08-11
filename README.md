# IINA Hybrid Keybindings

A custom **IINA input configuration** designed to combine the best parts of **YouTube's web-player controls, VLC-style keyboard shortcuts, and native macOS conventions**.

This preset is built for people who want a fast, consistent, keyboard-first experience when using [IINA](https://iina.io/).

> **Note:** This is an IINA input configuration, not a VLC keymap. VLC does not use this text-based input configuration format.

---

## Features

### Playback

Familiar playback controls inspired by YouTube and VLC:

| Key     | Action            |
| ------- | ----------------- |
| `Space` | Play / Pause      |
| `K`     | Play / Pause      |
| `F`     | Toggle fullscreen |
| `Esc`   | Exit fullscreen   |
| `S`     | Stop              |

---

### YouTube-style Seeking

The preset follows the familiar YouTube seeking model:

| Key         |    Seek |
| ----------- | ------: |
| `←`         |  -5 sec |
| `→`         |  +5 sec |
| `J`         | -10 sec |
| `L`         | +10 sec |
| `Shift + ←` |  -3 sec |
| `Shift + →` |  +3 sec |

This makes switching between IINA and YouTube feel much more natural.

---

### VLC-style Jump Tiers

For larger jumps, modifier keys provide progressively larger seeking intervals:

| Shortcut           |    Seek |
| ------------------ | ------: |
| `Alt + ←/→`        | ±10 sec |
| `Ctrl + ←/→`       | ±60 sec |
| `Ctrl + Alt + ←/→` |  ±5 min |

There are also macOS-oriented equivalents using `⌘`:

| Shortcut    |    Seek |
| ----------- | ------: |
| `⌥⌘ + ←/→`  | ±10 sec |
| `⇧⌘ + ←/→`  | ±60 sec |
| `⇧⌥⌘ + ←/→` |  ±5 min |

This gives you both **Windows/VLC muscle memory** and **Mac-native alternatives**.

---

### YouTube Percent Seeking

The number row works exactly like YouTube:

```text
0 → 0%
1 → 10%
2 → 20%
3 → 30%
4 → 40%
5 → 50%
6 → 60%
7 → 70%
8 → 80%
9 → 90%
```

This is especially useful for quickly jumping around long videos.

---

## Volume Controls

Multiple volume controls are available depending on how precise you want to be.

| Key           | Action      |
| ------------- | ----------- |
| `↑`           | Volume +5   |
| `↓`           | Volume -5   |
| `Volume Up`   | Volume +2   |
| `Volume Down` | Volume -2   |
| `M`           | Toggle mute |
| `Mute`        | Toggle mute |
| `Alt + ⌘ + ↓` | Toggle mute |

The arrow keys provide fast adjustment, while the media-volume keys provide finer control.

---

## Playlist & Chapter Controls

| Key        | Action                 |
| ---------- | ---------------------- |
| `N`        | Next playlist item     |
| `P`        | Previous playlist item |
| `⌘ + →`    | Next                   |
| `⌘ + ←`    | Previous               |
| `⌘ + Z`    | Shuffle playlist       |
| `Ctrl + D` | Add chapter +1         |
| `Ctrl + U` | Add chapter -1         |

---

## Frame-by-Frame Playback

Useful for lectures, tutorials, debugging videos, animation analysis, and other frame-sensitive work.

| Key | Action         |
| --- | -------------- |
| `,` | Previous frame |
| `.` | Next frame     |
| `E` | Next frame     |

---

## Playback Speed

Quickly adjust playback speed without opening a menu.

| Key     | Action                |
| ------- | --------------------- |
| `[`     | -0.1×                 |
| `]`     | +0.1×                 |
| `<`     | -0.25×                |
| `>`     | +0.25×                |
| `=`     | Reset to 1×           |
| `⌘ + =` | Multiply speed by 1.5 |
| `⌘ + -` | Multiply speed by 0.5 |

This makes the preset particularly useful for **lectures, tutorials, documentation, and educational videos**.

---

## Subtitle & Audio Controls

| Key         | Action                     |
| ----------- | -------------------------- |
| `V`         | Cycle subtitles            |
| `B`         | Cycle audio tracks         |
| `C`         | Toggle subtitle visibility |
| `Shift + S` | Toggle subtitle visibility |
| `Shift + J` | Subtitle delay +0.1s       |
| `Shift + H` | Subtitle delay -0.1s       |
| `Shift + G` | Audio delay +0.1s          |
| `Shift + F` | Audio delay -0.1s          |
| `D`         | Toggle deinterlacing       |
| `⌘ + L`     | A-B loop                   |
| `⌘ + L`     | Toggle infinite loop       |

---

## Video & Window Controls

### Window Scaling

| Key         |         Scale |
| ----------- | ------------: |
| `⌘ + 0`     |          0.5× |
| `⌘ + 1`     |            1× |
| `⌘ + 2`     |            2× |
| `Z`         | Cycle scaling |
| `Shift + Z` | Reverse cycle |

### Aspect Ratio

`A` cycles through:

```text
Auto
16:9
4:3
1:1
16:10
2.21:1
2.35:1
2.39:1
5:4
```

### Screenshot

```text
Alt + ⌘ + S
```

Take a screenshot without reaching for the mouse.

---

## Hardware Media Keys

The configuration also maps common media keys:

```text
Play        → Play / Pause
Pause       → Pause
Play/Pause  → Play / Pause
Stop        → Stop
Forward     → +60 sec
Rewind      → -60 sec
Next        → Next playlist item
Previous    → Previous playlist item
Close       → Quit
Power       → Quit
```

This means the keyboard's dedicated media controls continue to work naturally.

---

# Why This Preset?

Most media players force you to choose between different shortcut philosophies.

For example:

* YouTube has excellent **5-second / 10-second seeking**
* VLC has useful **large jump intervals**
* macOS applications often use **Command-based shortcuts**
* IINA has powerful functionality but its default mappings may not match everyone's muscle memory

This configuration combines them into one system.

### The idea

```text
                  IINA
                   │
       ┌───────────┼───────────┐
       │           │           │
    YouTube       VLC        macOS
       │           │           │
    ±5 / ±10    ±60 / ±300   ⌘ shortcuts
       │           │           │
       └───────────┼───────────┘
                   │
          Hybrid Keybindings
```

---

# What Makes It Different?

### 1. YouTube + VLC Instead of Choosing One

You don't have to abandon familiar shortcuts when moving between platforms.

YouTube-style:

```text
← →     ±5 sec
J / L   ±10 sec
0–9     percentage seeking
```

VLC-style:

```text
Alt + ← →          ±10 sec
Ctrl + ← →         ±60 sec
Ctrl + Alt + ← →   ±5 min
```

---

### 2. Multiple Seeking Granularities

The configuration provides several levels of precision:

```text
±3 sec
±5 sec
±10 sec
±60 sec
±5 min
```

This makes it possible to make both tiny corrections and large jumps without opening IINA's interface.

---

### 3. Mac + Windows Muscle Memory

Instead of replacing Windows/VLC shortcuts on macOS, this preset keeps them while also providing Command-based alternatives.

You can therefore use whichever shortcut feels natural.

---

### 4. Keyboard-First Workflow

The goal is to minimize mouse usage.

Common operations such as:

* playback
* seeking
* volume
* subtitles
* audio tracks
* speed
* fullscreen
* screenshots
* playlist navigation
* frame stepping
* looping
* aspect ratio
* window scaling

can all be performed from the keyboard.

---

### 5. Designed Around Real Media Consumption

The mappings aren't just a collection of random shortcuts.

They prioritize operations that are frequently used while watching:

```text
Watch
 ↓
Pause
 ↓
Seek
 ↓
Fine-tune position
 ↓
Adjust speed
 ↓
Adjust subtitles/audio
 ↓
Resume
```

The most frequently needed controls therefore have short, memorable keys.

---

# Installation

1. Open IINA.
2. Open **IINA → Settings → Key Bindings**.
3. Import or replace your input configuration with the provided configuration file.
4. Restart IINA if necessary.

The main configuration file is:

```text
input.conf
```

---

# Compatibility

Designed for:

* macOS
* IINA
* Keyboard-first workflows
* Users familiar with YouTube controls
* Users familiar with VLC controls

This configuration is **not intended to be used directly by VLC**.

---

# Philosophy

The goal isn't to create the largest possible keymap.

The goal is to make common media-player actions:

**fast, predictable, memorable, and consistent.**

If you already use YouTube, VLC, and macOS regularly, this preset attempts to make IINA feel familiar to all three at once.

---

## License

Use, modify, and adapt the configuration for your own workflow.

If you improve the mappings, feel free to share your version.
