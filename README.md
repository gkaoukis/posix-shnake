# Shnake (POSIX Version)

A lightweight, terminal-based Snake game written in pure POSIX shell.
This version is adapted from [shanemcdo/shnake](https://github.com/shanemcdo/shnake/tree/main).

## Features

- POSIX Compliant: Runs on standard `/bin/sh` without needing Bash extensions.

- Universal RNG: Uses `/dev/urandom` via `od` instead of `$RANDOM`.

- Portable Input: Uses `stty` and `dd` for non-blocking input handling instead of read -t.

## Controls
```
| Key |   Action   |
|:---:|:----------:|
| W   | Move Up    |
| A   | Move Left  |
| S   | Move Down  |
| D   | Move Right |
| Q   | Quit Game  |
```