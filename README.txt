# Shawn Ryan Show Scraper

This folder contains a Python script that scrapes episode metadata from The Shawn Ryan Show and writes the results to an Excel workbook. It is intended to provide researchers with data for analyzing this popular show.

Folder layout:

```text
shawn_ryan_show/
├── README.txt
├── .gitignore
├── .venv/
├── shawn_ryan_show_scraper_script.py
└── shawn_ryan_episodes.xlsx
```

Copy and paste this block into Terminal:

```bash
cd insert-file-path-here/shawn_ryan_show
python3 -m venv .venv
source .venv/bin/activate
python3 -m pip install --upgrade pip
python3 -m pip install requests beautifulsoup4 openpyxl
python3 shawn_ryan_show_scraper_script.py
deactivate
```

The scraper writes the output workbook to:

```text
shawn_ryan_episodes.xlsx
```

The `python3 shawn_ryan_show_scraper_script.py` line does not need a full file path because the `cd` line above already moves Terminal into the `shawn_ryan_show` folder.
