# Port Scanner (Python)

## Overview
A simple TCP port scanner written in Python using the `socket` module. It loops through a port range and reports ports that respond as open.

Notes: This script writes output to a local text file (e.g., keyfile.txt). It is intentionally simple as a fundamentals learning exercise.

## What it demonstrates
- User input
- `for` loops and ranges
- TCP sockets (`socket.socket`, `connect_ex`)
- Timeouts
- Exception handling (`KeyboardInterrupt`, `socket.error`)
- Basic banners / console output

## Requirements
- Python 3.x

Optional (for ASCII banner):
- `pyfiglet`

Install:
```bash
pip install pyfiglet
