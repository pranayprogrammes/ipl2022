

Exploratory data analysis of the **IPL 2022** season, built in a Jupyter Notebook using `pandas`, `seaborn`, and `matplotlib`. The project digs into match results, player performances, and win margins across all 74 matches of the season.

## Dataset

The analysis uses `IPL.csv`, which contains match-level data for the 2022 season with **74 rows** and **20 columns**, including:



## Questions Explored

- Which team won the most matches in IPL 2022?
- How often did the toss winner also win the match?
- What was the most common way of winning a match — by runs or by wickets?
- Which player won the most Player of the Match awards?
- Who were the top run-scorers of the season?
- Which bowlers picked up the most wickets, based on their best bowling figures?
- What were the biggest wins of the season (largest winning margins by runs)?

## What's Inside the Notebook

- **Data loading & cleaning**: reading the CSV, checking shape, data types, and null values
- **Match win distribution**: bar chart of wins by team
- **Toss vs. match outcome**: percentage of matches where the toss winner also won the match
- **Win type breakdown**: count plot of matches won by runs vs. wickets
- **Player of the Match**: bar chart of top award winners
- **Top scorers**: aggregated and ranked by total runs, with a bar chart of the top performers
- **Bowling performance**: parsing wicket counts from bowling figures and ranking top bowlers
- **Biggest wins**: top 3 matches with the largest winning margins (by runs)

## Tech Stack

- Python
- pandas
- numpy
- seaborn
- matplotlib

## How to Run

1. Clone the repository
2. Make sure `IPL.csv` is in the same directory as the notebook
3. Install dependencies:
   ```bash
   pip install pandas numpy seaborn matplotlib
   ```
4. Open and run `ipl22.ipynb` in Jupyter Notebook / JupyterLab




