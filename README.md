# The Sims 3 Management Program

[![license](https://img.shields.io/github/license/jonaheinke/the-sims-3-management-program)](LICENSE)
[![code size](https://img.shields.io/github/languages/code-size/jonaheinke/the-sims-3-management-program)](#)

This is a simple python script to clear all the caches of The Sims 3. It is written in Python 3.10 and uses tkinter for the GUI.

It is intended to launch before every gameplay. You have to take care of that yourself. Instructions on how to do that are listed at Create a desktop shortcut.

## Screenshots

Light Mode                | Dark Mode                |
:------------------------:|:------------------------:|
![](screenshot_light.png) | ![](screenshot_dark.png) |

## Usage

### All Command line arguments

| Name      | Option        | Description                         |
|-----------|---------------|-------------------------------------|
| Help      | `-h, --help`  | show help message                   |
| Lightmode | `-l, --light` | switch to light mode                |
| Debug     | `-d, --debug` | enable debug mode (not recommended) |

### Run script

Make sure Python 3.10 or higher is installed. Only tkinter is required as an external dependency.

```bash
python -V
pip install tk -U
git clone --recurse-submodules https://github.com/jonaheinke/the-sims-3-management-program.git
python the-sims-3-management-program/main.py
```

### Optional: Create a desktop shortcut



## Known Issues

Planned:
- None

Waiting list:
- The main menu logo is still the latest installed expansion or stuff pack logo.

Won't be fixed:
- None

## Credits

used tkinter theme: [Forest theme by rdbende](https://github.com/rdbende/Forest-ttk-theme)