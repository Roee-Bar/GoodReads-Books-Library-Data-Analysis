# Goodreads Library Analysis Project

## Overview

This project involves gathering data from my Goodreads library and analyzing it to gain insights. The goals are:

- Export my full Goodreads library data
- Clean and process the raw CSV data
- Analyze reading trends and statistics 
- Identify insights related to favorite authors, genres, etc.

## Data Sources

The primary data source is a CSV export downloaded directly from Goodreads containing metadata on all books in my account library. This includes information like title, author, publication date, genres, review data, shelves, etc.  

Additional data is gathered by web scraping supplemental information from the Goodreads website as needed.

## Contents

The project contains the following key files:

- `GlobalGoodReadsBooksAnalysis.ipynb`: Notebook with code to scrape additional book data from Goodreads
- `my_goodreads_library_export_*.csv`: Raw CSV export from Goodreads
- `MyGoodReadsBooksAnalysis.ipynb`: Notebook to clean and process raw CSV data

The output is a cleaned CSV dataset for further analysis and visualization.

## Next Steps

Potential next steps for analysis:

- Reading statistics over time
- Favorite authors and genres 
- Book length and format trends
- Identifying book recommendations
