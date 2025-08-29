# Oglasi.rs Listings Scraper

This repository contains a **Jupyter Notebook** script that automatically collects sale listings from [oglasi.rs](https://www.oglasi.rs).  

It covers multiple categories:  

- Apartments  
- Houses  
- Business premises (offices, shops)  
- Vacation houses  

## How it works

The process is automated with **GitHub Actions**.  
Every week, GitHub runs the notebook, scrapes all active sale listings from the above categories, and saves the results as a CSV file in this repository.

CSV files are named according to the scraping date (e.g. `prodaja 2025-08-29.csv`).

## Frequency

- The workflow runs **automatically every Friday at 12:00 Belgrade time** (10:00 UTC).  
- It can also be triggered manually through the GitHub interface (**Run workflow** button).

## Technologies

- Python (pandas, requests, BeautifulSoup)  
- Jupyter Notebook  
- GitHub Actions (automation)

---