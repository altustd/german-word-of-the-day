# german-word-of-the-day
Retrieves a German word of the day by scraping  www.germaneveryday.com

"""
Created on Mon Jan  5 19:19:15 2026

Author: Troy Altus
"""

"""
German Word of the Day (GermanWOD)

DESCRIPTION
-----------
This script retrieves a German "Word of the Day" by scraping a publicly
available language-learning website. It extracts the featured German word
and its definition and prints them to the console.

The script is intended for:
- Language learners
- Python practice (HTTP requests, HTML parsing)
- Simple daily automation tasks

IMPORTANT NOTES
---------------
- This script does NOT use an official API.
- The HTML structure of the source website may change at any time.
- If the site layout changes, the script may return 'N/A' values.
- Use responsibly and respect website terms of service.

USAGE
-----
From the command line:
    python GermanWOD.py

Show help:
    python GermanWOD.py --help

OPTIONAL FLAGS
--------------
--verbose
    Print additional diagnostic information (HTTP status, parsing steps).

DEPENDENCIES
------------
- requests
- beautifulsoup4

Install dependencies:
    pip install requests beautifulsoup4

AUTHOR
------
Troy Altus (learning project)

"""
