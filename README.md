# 🦇 Batman Box Office Analysis (1966–2022)

A data science project analysing every theatrical Batman film across six decades — exploring budgets, worldwide gross, ROI, critical reception, and era comparisons.

## Project Overview

This notebook investigates what makes a Batman film financially successful. It covers 12 theatrical releases from the 1966 Adam West film through to Matt Reeves' 2022 *The Batman*, including the animated *Mask of the Phantasm* (1993).

## Key Questions Answered

- Which Batman film had the best return on investment (ROI)?
- Does a bigger budget guarantee a bigger box office return?
- Which era — Burton, Nolan, DCEU — performed best financially and critically?
- Why did *Mask of the Phantasm* (83% on RT) earn less than its $6M budget?
- How have budgets inflated over six decades?

## Analyses & Visualisations

| # | Analysis |
|---|---|
| 1 | Worldwide gross by film (bar chart, colour-coded by era) |
| 2 | ROI % ranked from best to worst |
| 3 | Budget vs worldwide gross scatter plot with trend line |
| 4 | Rotten Tomatoes score vs gross — the Mask of the Phantasm anomaly |
| 5 | Era comparison — avg gross, avg ROI, avg RT score |
| 6 | Budget inflation over time (1966–2022) |
| 7 | Animated vs live action comparison |
| 8 | Key findings summary |

## Dataset

`batman_data.csv` — manually compiled from Box Office Mojo, The Numbers, and Rotten Tomatoes.

| Column | Description |
|---|---|
| title | Film title |
| year | Release year |
| budget_m | Production budget ($M) |
| worldwide_gross_m | Worldwide box office gross ($M) |
| domestic_gross_m | US/Canada gross ($M) |
| rt_score | Rotten Tomatoes critic score (%) |
| audience_score | Audience score (%) |
| director | Director(s) |
| batman_actor | Actor who played Batman |
| era | Production era (Burton / Nolan / DCEU etc.) |
| animated | Yes / No |
| roi | Return on investment % (calculated) |
| profit_m | Profit in $M (calculated) |

## Tech Stack

- Python 3
- pandas
- matplotlib
- seaborn
- scipy
- Jupyter Notebook

## How to Run

```bash
# Clone the repo
git clone https://github.com/karthikthirunagari01/batman-box-office-analysis.git
cd batman-box-office-analysis

# Install dependencies
pip install pandas matplotlib seaborn scipy jupyter

# Launch notebook
jupyter notebook batman_analysis.ipynb
```

## Key Findings

- **Best ROI:** Batman (1989) — Tim Burton's original on a $35M budget returned $411M worldwide
- **Worst ROI:** Batman: Mask of the Phantasm — box office bomb despite an 83% RT score
- **Top Era:** Christopher Nolan's trilogy averaged over $820M per film
- **Anomaly:** Mask of the Phantasm proves critical quality alone does not guarantee box office success — marketing and release strategy matter equally
- **Budget trend:** Production budgets grew from $1.5M (1966) to $250M (2012) — a 16,567% increase

## Author

Karthik Thirunagari — [github.com/karthikthirunagari01](https://github.com/karthikthirunagari01)
