# File Archiver

This program collects files from a specified directory and compresses them into RAR archives, with a maximum size limit of 2 GB per archive. The naming convention for the RAR files is based on the folder name, with a suffix added to indicate the archive number (e.g., `_1`, `_2`, etc.). The created archive files are stored in the selected folder.

## Features

- Collects files from a specified path.
- Creates RAR archives with a maximum size of 2 GB.
- Names the archives based on the folder name with incremental suffixes.

## Usage

1. Specify the directory path from which to collect files.
2. Run the program to create the RAR archives.
3. The archives will be named according to the folder name and sent to your Telegram.

## Requirements

- Python 3.x
- Required libraries: os, re, zipfile

