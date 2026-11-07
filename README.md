# Library Management Portal

A console-based backend portal for managing a library, written in plain Python
and run in Google Colab.

## Features
- Login with roles (librarian and member)
- Add, search and view books
- Issue and return books with due dates
- Late-return fine calculation
- Library summary report
- JSON file storage with error handling

## Files
- `Library_portal.ipynb`: the full notebook (code, outputs, test runs)
- `books.json`, `members.json`, `issued.json`: data files

## How to run
1. Open `Library_portal.ipynb` in Google Colab.
2. Run all cells from top to bottom (Runtime, then Run all).
3. Log in with `admin` / `admin123` (librarian) or `ali` / `ali123` (member).

## Team
- Noor: file handling, login, add record, issue/return, GitHub setup
- Bushra: validation, search, fines, report, documentation
