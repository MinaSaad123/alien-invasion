# Alien Invasion — Python Crash Course, Third Edition

The completed Alien Invasion game from Chapters 12–14 of **Python Crash Course, Third Edition**, by Eric Matthes (No Starch Press).

The eight Python source files and both bitmap images are unchanged copies of the author's official `chapter_14/scoring` snapshot. No exercise extensions, alternate graphics, sounds, or gameplay changes have been added.

## Run

Install Python 3.11 or newer. Open a terminal in this project directory:

```bash
python -m venv .venv
```

Activate the environment:

- macOS/Linux: `source .venv/bin/activate`
- Windows PowerShell: `.venv\Scripts\Activate.ps1`
- Windows Command Prompt: `.venv\Scripts\activate.bat`

Then install and run:

```bash
python -m pip install -r requirements.txt
python alien_invasion.py
```

On systems where the command is `python3`, use that in place of `python`. Run from the project directory so the book's relative image paths resolve correctly. The game opens a 1200 × 800 window.

## Controls

| Action | Control |
| --- | --- |
| Start or restart | Click **Play** |
| Move | Left and right arrow keys |
| Shoot | Spacebar |
| Quit | Q or close the window |

Shoot the fleet to advance levels. Each cleared fleet increases speed and alien point values. The scoreboard shows the score, session high score, level, and remaining ships. The high score resets when the program closes, as in the book's base project.

## Source and attribution

- Author: **Eric Matthes**
- Book: [Python Crash Course, Third Edition](https://nostarch.com/python-crash-course-3rd-edition)
- [Official project snapshot](https://github.com/ehmatthes/pcc_3e/tree/3690082cad0aad58cedb4face741aa025d6e8d73/chapter_14/scoring)
- Upstream commit: `3690082cad0aad58cedb4face741aa025d6e8d73`

This repository packages the author's example for study; it does not claim original authorship of the game code or artwork. Setup instructions and dependency metadata were added here. No additional license is asserted over the upstream material.
