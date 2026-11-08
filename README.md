# Vega

Personal observation planning and logging tool for observational astronomers.

> **Status:** early development. The features below are planned unless marked as done.

## The problem

Logging observations in a paper notebook means using a torch in the dark, which costs you dark adaptation. Handwritten notes are also hard to search or compare later. Vega is meant to replace the physical hardcopy notebook with a planner and log designed for use at the eyepiece.

## Features

- [ ] **Sky planner:** for a given location, list planets, the Moon (phase, rise and set), and bright objects visible tonight, with altitude and best viewing time (Skyfield)
- [ ] **Target ranking:** rank objects by altitude, Moon interference, and your equipment
- [ ] **Observation log:** record target, time, equipment, seeing, rating, and notes in SQLite
- [ ] **Plan-to-log link:** start a log entry from tonight's plan with time, location, and equipment filled in
- [ ] **History and stats:** search past sessions and see what you haven't observed yet
- [ ] **Red night mode** and **offline use**
- [ ] **Web interface** (after the command-line version works)

## Tech stack

- Python 3
- [Skyfield](https://rhodesmill.org/skyfield/) for astronomical calculations
- SQLite for local storage
- pytest for tests

## Getting started

```bash
git clone https://github.com/<your-username>/Vega.git
cd Vega
python -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

Usage instructions will be added as features are completed.

## Roadmap

1. Command-line planner: tonight's visible objects
2. Observation logging with SQLite
3. Link planning to logging
4. Equipment profiles and target ranking
5. History, search, and stats
6. Web interface with red night mode

## Privacy

All data stays on your device. Vega uses no accounts, tracking, or third-party personal data.

## License

No license has been specified yet. All rights reserved by the author.

## Author

Shriram, observational astronomer.
