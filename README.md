# Metacritic Games Analysis (2011–2019)

## Overview

This project analyzes critic and user review scores for over 5,500 video games released between 2011 and 2019, using data sourced from Kaggle. The goal was to identify trends in how critics and users evaluate games differently across genres, platforms, and ESRB ratings, and to explore how cultural shifts in the gaming industry may have influenced scoring patterns over time.

## Dataset

- **Source:** [Kaggle — Metacritic Games Dataset](https://www.kaggle.com)
- **Size:** 5,500+ games released between 2011 and 2019
- **Key fields:** Game title, platform, genre, ESRB rating, release date, Metascore, user score

Note: This dataset is not representative of all games released during this period. Not all released games have Metacritic entries, and user scores are susceptible to review bombing which may skew results for certain titles.

## Tools & Libraries

- Python, pandas, numpy, matplotlib, seaborn
- Jupyter Notebook

## Key Findings

- Critic and user scores were nearly identical in 2011 but gradually diverged, with critic scores increasing and user scores declining over time — likely influenced by the rise of microtransactions, review bombing, and shifting player demographics
- Critics and users broadly agree on which genres produce quality games, but notable differences exist — users rate console RPGs higher while critics favor fighting games
- A correlation of 0.55 between Metascore and user score indicates a moderate relationship, with meaningful divergence at the individual game and genre level
- Games with the largest critic–user score gaps tend to be high-profile titles with passionate fan bases or controversial business practices

## Repository Contents

| File | Description |
|------|-------------|
| `Metacritic_games.ipynb` | Jupyter Notebook with full analysis and visualizations |
| `metacritic_games.csv` | Original dataset as downloaded from Kaggle |
| `metacritic_games_cleaned.csv` | Cleaned dataset with genre reassignments and engineered features |
| `insights_brief.docx` | Written summary of findings and recommendations |
| `visualizations/` | Folder containing exported chart images |

## How to Run

1. Clone or download this repository
2. Ensure Python is installed with the following libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`
3. Open `Metacritic_games.ipynb` in Jupyter Notebook
4. Place the CSV files in the same directory as the notebook
5. Run all cells in order from top to bottom
