# Global Country Data Analyst Project

A Python-based data analysis project built to explore, filter, sort, and navigate a dataset of 100 countries using **Pandas**. 

## Project Overview
This project simulates a data investigation workflow where raw, unordered global data is loaded, cleaned, searched, and structured using foundational data manipulation techniques.

## Key Operations Covered
- **Dataset Inspection:** Loading CSV files, analyzing dimensions (`len`, `shape`), inspecting head/tail rows, and reviewing data types (`info()`).
- **Data Filtering & Selection:** Selecting subset columns, filtering rows by rank thresholds, and matching text patterns (`str.contains()`).
- **Conditional Matching:** Utilizing `.isin()` to filter specific target lists (e.g., favorite countries).
- **Sorting Data:** Performing single-column ascending/descending sorting and multi-column hierarchical sorting (`sort_values()`).
- **Regional Analysis:** Extracting and filtering records by continent.
- **Index Management:** Transforming columns into single and multi-level indexes and navigating data frames using `.loc` and `.iloc`.

## Tech Stack
- **Language:** Python 
- **Library:** Pandas

## Dataset
- **File:** `world_countries_unordered.csv` (100 rows containing real country names, capitals, continents, population metrics, area, and randomized ranks).
