Automated Backup Script with Logging


Description

A Python script that automates the process of backing up files/folders by compressing them into timestamped ZIP archives. It also logs each backup with file names and backup time for reference or audits.

Features

- Automatic ZIP backups of files or folders
- Timestamps added to filenames
- Log file (`backup.log`) with detailed info
- Simple and customizable script


Technologies

- Python 3.x (standard library only)


Getting Started

1. #Create and activate a virtual environment
2. ```bash
3. python -m venv .venv

4. # Windows
5. .\.venv\Scripts\activate

6. # macOS/Linux
7. source .venv/bin/activate

8. No external dependencies required

Run the app

python backup_script.py

Requirements

Uses only built-in Python modules:

os, shutil, zipfile, datetime, logging
