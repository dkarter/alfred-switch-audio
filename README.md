# :speaker: SwitchAudio Alfred Workflow

Yet another audio input/output switching interface for [SwitchAudioSource](https://github.com/deweller/switchaudio-osx/)

Tested with Alfred 5 and macOS Monterey.

## Motivation

All the other workflows I tried were incompatible with macOS Monterey, so I
figured it would be easier to just build my own

## Prerequisites

You need to have both SwitchAudioSource and JQ installed on your mac. This is
most easily done via Homebrew:

```bash
brew install switchaudio-osx jq
```

Also you will need Alfred Powerpack. This workflow was tested with Alfred 5
only.

## Installation

Download the workflow from GitHub and open it.

## Usage

In Alfred type

`;so` — to switch output device

`;si` — to switch input device

## Screenshots

Output selection
![output selection](./screenshots/output.png)

Input selection
![input selection](./screenshots/input.png)


