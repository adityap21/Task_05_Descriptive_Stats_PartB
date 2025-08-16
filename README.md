# Task 05 – Descriptive Statistics (NBA Data Analysis)

## Overview
This repository contains the expanded Task 5 submission.  
It analyzes NBA player statistics from the 2022–23 season using Python, and compares those results with ChatGPT’s narrative answers.  
The goal is to show where Python is needed for exact, reproducible results and where AI tools can help with explanation.

## Dataset
- Sample of 50 NBA players from the 2022–23 season.  
- Columns: Player, PTS, REB, AST, STL, BLK, FG%, 3P%, FT%.  
- Percentages normalized to 0–1 if necessary.  

## Questions Answered
1. Who scored the most points per game?  
2. Who is the best all-around player (PTS + REB + AST)?  
3. Who is the most complete player?  
4. Who is the best shooter (FG%, 3P%, FT%)?  
5. How many players averaged at least 25 points per game?  
6. How many players averaged at least 8 assists per game?  

## Method
- Cleaned and normalized the dataset.  
- Used Python (pandas, matplotlib, scipy) for analysis and visualizations.  
- Asked ChatGPT the same questions for comparison.  
- Documented matches, mismatches, and limitations.  
- Saved outputs (`summary_answers.json`, `q3_composite_table.csv`) for reporting.  

## Visuals
- Top-10 scorers bar chart  
- Histogram of assists  
- Scatter plot of points vs assists  

## Files in this Repo
- `Task_05_Complete_NBA_LLManalysis_NbaData.ipynb` – Jupyter Notebook with code, analysis, and visuals.  
- `Task_05_Descriptive_Stats_Nba_data.docx` – Written report.  
- `README.md` – This file.  

## How to Run
1. Ensure `Nba_data.csv` is in the repo root.  
2. Open `Task_05_Complete_NBA_LLManalysis_NbaData.ipynb` in Jupyter or VS Code.  
3. Run all cells to reproduce results and generate charts.  
4. Use the saved outputs in your reporting form.  
