# AI Web Scraper with Optional NLP Enrichment

## Overview
This project scrapes target websites, extracts structured fields, cleans data, and optionally enriches text using NLP.

## Setup
1. Install dependencies:
   ```
   pip install -r requirements.txt
   python -m spacy download en_core_web_sm
   ```
2. Add your URLs in `input_urls.csv`.

## Run
```
python main.py
```

## Output
- `output.csv`: Structured scraped data
- `run.log`: Scraping summary and errors
