# Which Building Age Gives You the Most m² per CHF in Switzerland?

This project analyzes whether certain building-age categories offer better m²/CHF value in the Swiss rental market.

## Data Sources
- BFS Building Age datasets (bau515od5155–5158)
- ~50 scraped rental listings (Homegate or Immoscout24)

## Folder Structure
/Data                # BFS CSVs + scraped data + SQLite DB
/Notebooks           # Jupyter notebooks for scraping, cleaning, EDA, modelling
/src                 # Python scripts (scraper, cleaning functions, helper funcs)
/Reports             # Final slides, report, figures

## Requirements
See `requirements.txt` for all Python dependencies.
