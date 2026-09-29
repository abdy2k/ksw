# KSW — Khmer Smart Writer

A lightweight Khmer keyboard driver / input engine for typing Khmer Unicode text on Windows and Linux.

KSW lets you type Khmer directly using a QWERTY keyboard layout, without needing to install a full IME suite. It's designed to be simple, portable, and easy to set up.

## Features

- Khmer Unicode text input via a QWERTY-mapped layout
- Native driver for **Windows** (`ksw.exe`) and **Linux** (`ksw`)
- Browser-based reference/demo layout (`keyboard.html`)
- Printable QWERTY-to-Khmer keyboard layout chart (`qwerty_ksw_keyboard.pdf`)
- MIT licensed — free to use, modify, and distribute

## Installation

### Windows

1. Download `ksw.exe` from this repository.
2. Run it directly — no installation required.
3. Refer to `qwerty_ksw_keyboard.pdf` for the key layout.

### Linux

1. Download `kswk.zip` from this repository.
2. Extract it:
   ```bash
   unzip kswk.zip
   or ksw_rel.7z
   cd kswk
   ```
3. Run the setup script included inside the extracted folder to install and launch the driver.
4. See `ksw_linux_instruction.txt` for detailed steps specific to your distro.

### Browser demo

Open `keyboard.html` in any modern browser to try the Khmer layout without installing anything.

## Keyboard Layout

<img width="614" height="263" alt="image" src="https://github.com/user-attachments/assets/1b792468-7eb6-4607-8343-fd7703237eda" />

The `qwerty_ksw_keyboard.pdf` file contains the full key mapping — print it out or keep it open alongside your keyboard while you learn the layout.

## Why KSW?

Most Khmer input tools (like Google's Khmer Input Tools or NIDA Khmer Unicode) are either browser extensions, mobile-only, or require a heavier install. KSW aims to be a minimal, native, cross-platform driver that just works.

## License

MIT © 2026 abdy2k — see [LICENSE](LICENSE) for details.

## Contributing

Issues and pull requests are welcome. If you find bugs in the layout mapping or run into install problems on a particular Linux distro, please open an issue.
