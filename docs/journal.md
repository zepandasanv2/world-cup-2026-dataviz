# Project Journal – World Cup 2026 DataViz

This is a daily log of progress on building an interactive Power BI dashboard for the 2026 FIFA World Cup.

---

## Day 1 – 2025-03-22
- Brainstormed project objectives with ChatGPT
- Defined the structure for the `teams` dataset (team name, code, ranking, qualification status, coordinates, etc.)
- Planned a color-coded world map based on team status (Qualified, In Progress, Eliminated)
- Defined Git workflow with branches: main, develop, feature/*
- Created initial project folder structure

---

## Day 2 – 2025-03-23
- Initialized Git repository and structured the project folders
- Created teams dataset from the RestCountries API using a script
- Scraped the list of FIFA member countries from Wikipedia
- Merged RestCountries data with FIFA members using `pandas`
- Handled mismatches and added manual corrections for non-standard teams (e.g. England, Tahiti)
- Created a cleaned and complete `fifa_with_countries.csv` dataset
- Moved all ETL logic into a single Jupyter notebook `ETL.ipynb`
- Removed `scripts/` folder and added `venv/` to `.gitignore`

---
