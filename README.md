# KMonad Configuration for ErgoDox EZ

This repository contains a configuration file for [KMonad](https://github.com/kmonad/kmonad) designed for the ErgoDox EZ keyboard.

## Requirements

- A recent version of **KMonad** (v0.4 or later is recommended).
- Linux with `uinput` support enabled.

## Usage

1. Install or build KMonad for your system.
2. Launch KMonad with `config.kbd`:
   ```
   kmonad config.kbd
   ```
3. The configuration expects the keyboard to appear as `/dev/input/by-id/usb-ZSA_Technology_Labs_Ergodox_EZ-event-kbd`. Adjust the `input` path in `config.kbd` if your device differs.

The output is a virtual device named `KMonad ergo`.

## Features

- Several layers for text editing, media control, and special functionality (`turbo0`, `turbo1`, `turbo2`, `upcase`, `upword`).
- Extensive use of tap-hold keys and macros for efficient shortcuts.
- Controls for keyboard backlight and media playback.

## Customization

Edit `config.kbd` to change key assignments or to point to the correct input device on your system.

## License

This configuration is provided as-is without warranty. Feel free to adapt it to your needs.
