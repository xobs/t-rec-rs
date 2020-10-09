# Terminal Recorder - t-rec

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

Blazingly fast terminal recorder that generates animated gif images for the web written in rust.

# Demo

![demo](./docs/demo.gif)

## Features

- Screenshoting your terminal with 4 frames per second (every 250ms)
- Generates high quality small sized animated gif images
- Runs (only) on MacOS
- Uses native efficient APIs
- Runs without any cloud service and entirely offline
- No issues with terminal sizes larger than 80x24
- No issues with fonts or colors
- No issues with curses based programs
- No issues with escape sequences
- No record and replay - just one simple command to rule them all 
- Written in Rust 🦀

## Install

Soon it will be ready

## Usage

```sh
❯ t-rec
```

or with specifying a different program to launch

```sh
❯ t-rec /bin/sh
```

## Contribute

To contribute to t-rec you can either checkout existing issues [labeled with `good first issue`][4] or [open a new issue][5] and describe your problem.
Also every PR is welcome. Support for Linux and Windows needs to be done.

## License

- **[GNU GPL v3 license](https://www.gnu.org/licenses/gpl-3.0)**
- Copyright 2020 © [Sven Assmann][2].

[2]: https://www.d34dl0ck.me
[4]: https://github.com/sassman/t-rec-rs/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22
[5]: https://github.com/sassman/t-rec-rs/issues/new/choose