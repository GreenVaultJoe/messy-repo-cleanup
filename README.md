# Water Quality Data Analysis – Messy Repo Cleanup

## 1. Project Title & Description
This repository contains a small water-quality analysis project used to practice good data stewardship.  
The goal is to organize data and analysis scripts so results are reproducible.

## 2. File Organization
- data/
    - raw_data/ – Original input files exactly as received (read-only, never edited).  
    - processed_data/ – Cleaned or transformed datasets created from the raw data.  
    - analysis/ – Intermediate analysis outputs, exploratory tables, or model results.  
    - metadata/ – Data dictionaries, collection notes, and other documentation about the datasets.  
    - outputs/ – Final figures, tables, and reports ready to share.  
    - archive/ – Old or superseded files kept for reference but not used in current analysis.  
- scripts/ – Version-controlled R/Python scripts for cleaning data and running analyses.  


## 3. Requirements
- Software: R (≥ 4.0.0), RStudio (optional but recommended).  
- R packages: `tidyverse` (for data wrangling and plotting), plus 'dyplr' and `fs` for file paths.  
- Optional: Python 3.x if using the provided data-cleaning utilities script.

## 4. Contact Info
Maintainer: Joe Boccuzzi
Email: joe.boccuzzi@ctgreenbank.com

## 5. License
This repository is for educational use only as part of a data stewardship course.  
You may reuse the code and structure for coursework or learning, but not for commercial purposes.
