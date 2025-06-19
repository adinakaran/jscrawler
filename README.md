# JavaScript File Extractor

A Python script that extracts JavaScript files from a given webpage URL and saves them to a local directory.

## Features

- Extracts both external JavaScript files (from `script` tags with `src` attribute)
- Identifies JavaScript URLs in inline scripts
- Handles relative URLs by converting them to absolute URLs
- Saves files with domain-prefixed names for easy identification
- Creates an output directory automatically if it doesn't exist

## Requirements

- Python 3.x
- BeautifulSoup4
- Requests

## Installation

1. Clone or download this repository
2. Install the required packages:
   ```bash
   pip install -r requirements.txt
Usage
bash
python js_extractor.py [URL]
Example:

bash
python js_extractor.py https://example.com
The script will:

Create a js_files directory (if it doesn't exist)

Download all found JavaScript files

Save them with names like example.com_1.js, example.com_2.js, etc.

Output
Script will display:

Number of JavaScript files found

Filename and size of each saved file

Any errors encountered during download

Notes
The script includes a basic User-Agent header to avoid being blocked by some websites

Only HTTPS and HTTP URLs are processed

Inline JavaScript is scanned for potential JS file URLs

text

These files provide:
1. The necessary dependencies in `requirements.txt`
2. Clear documentation in `README.md` including:
   - Description of what the script does
   - Installation instructions
   - Usage examples
   - Expected output
   - Important notes about functionality

The versions in requirements.txt are current stable versions of the packages as of my knowledge cutoff, but you may want to update them if needed.