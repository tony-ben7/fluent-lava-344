# Setup

## Requirements

- A modern OS (Windows, macOS or Linux)
- ~200 MB of free disk space

## Quick setup

1. Download or clone the repository.
2. Open a terminal in the project folder.
3. Run the bootstrap script for your platform.

```bash
# Linux / macOS
bash scripts/setup.sh
```

```bat
REM Windows
scripts\setup.bat
```

## Verifying the install

Run the smoke test:

```bash
python tests/smoke_test.py
```
