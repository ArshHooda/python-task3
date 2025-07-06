# Headline Scraper

This Python script scrapes headlines from a news website (BBC News by default) using BeautifulSoup and requests. It extracts headlines with specific HTML attributes for targeted scraping.

## Features

- Scrapes headlines based on specific `data-testid` and `class` attributes
- Handles HTTP requests with custom User-Agent header
- Outputs headlines with their metadata (class and test ID)
- Error handling for network requests and parsing

## Requirements

- Python 3.x
- BeautifulSoup4 (`bs4`)
- requests library

## Installation

```bash
pip install beautifulsoup4 requests
