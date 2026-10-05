# Study Assistant

A starter rule-based assistant for the CSC10014 course.

## Setup

Requirements: Python 3.10 or newer and Git.

On Windows PowerShell:

    py -m venv .venv
    .\.venv\Scripts\Activate.ps1
    python -m pip install -r requirements.txt
    python -m pip install -e .

On macOS or Linux:

    python3 -m venv .venv
    source .venv/bin/activate
    python -m pip install -r requirements.txt
    python -m pip install -e .

## Run

    python -m assistant "where is the IT helpdesk?"

Expected output:

    IT Helpdesk: room E.005, open Mon-Fri 08:00-17:00.

## Test

    python -m pytest -q

Expected result:

    4 passed

## Project structure

- `src/assistant/`: application source code
- `tests/`: automated tests
- `data/`: sample office data
- `scripts/`: environment checking scripts
- `docs/`: project documentation
- `ui/`: user interface placeholder