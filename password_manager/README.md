# Password Manager (Learning Project)

## Overview
A simple command-line “account create / login” demo that hashes passwords using SHA-256 and stores them in memory.

## What it demonstrates
- Dictionaries for storage
- Functions (`create_account`, `login`)
- Password hashing (`hashlib.sha256`)
- Hidden password input (`getpass`)
- Loops and menus (`while True`)
- Conditionals and comparisons

## Requirements
- Python 3.x

## Important Notes
- This is a **learning project** and not a production password manager.
- Accounts are stored **in memory only** (reset when the script exits).
- SHA-256 hashing here is educational; real systems use salted + slow hashes (bcrypt/argon2/scrypt).

## Suggested Improvements (future)
- Store accounts in a file (JSON) securely
- Add password strength checks
- Use salted hashing + a proper KDF
- Add account lockout / rate-limiting
