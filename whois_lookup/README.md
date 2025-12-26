# WHOIS Lookup (Python)

## Overview
A lightweight WHOIS lookup script using raw TCP sockets to query a WHOIS server and print the response.

## What it demonstrates
- Functions
- Sockets (`AF_INET`, `SOCK_STREAM`)
- Sending/receiving bytes (`send`, `recv`)
- Encoding/decoding (`encode`, `decode`)
- Returning values from functions

## Requirements
- Python 3.x

## Usage
Edit the domain in the script (or expand it to accept user input) and run.

## Notes / Improvements (future)
- Accept domain as CLI input (`argparse`)
- Handle different WHOIS servers (TLD-based routing)
- Improve parsing (extract registrar, dates, name servers)
- Add timeouts and better error handling
