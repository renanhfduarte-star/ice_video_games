# Video Game Market Analysis (Ice Online Store)

This repository contains a data analysis project that evaluates historical video game sales data to identify patterns that determine a game's success. 

## Project Overview

The primary goal of this project is to provide data-driven recommendations for the 2017 advertising campaigns of "Ice", an international online video game store. By analyzing platform life cycles, the impact of reviews, and regional preferences, this analysis helps optimize marketing budgets and campaign targeting.

## Tools & Technologies

*   **Python 3:** Core programming language.
*   **Pandas & NumPy:** Data cleaning, transformation, and aggregation.
*   **Matplotlib & Seaborn:** Data visualization (boxplots, scatter plots, line charts).
*   **SciPy:** Statistical hypothesis testing (Two-Sample t-test).
*   **Jupyter Notebook:** Interactive data analysis and reporting.

## Key Findings

| Insight Category | Key Finding |
| :--- | :--- |
| **Platform Life Cycle** | Gaming platforms typically exhibit a predictable 10-year life cycle from launch to market obsolescence. |
| **Review Impact** | A cross-platform analysis confirmed a universal market rule: professional critic scores have a moderate positive correlation with commercial success. User scores, however, show almost zero correlation across all major consoles. |
| **Regional Differences** | The NA and EU markets are very similar (heavily favoring Action/Shooter games on Home Consoles). The Japanese market is fundamentally different, dominated by Handheld consoles (Nintendo 3DS) and Role-Playing Games (RPG). |

## Strategic Recommendations

*   **2017 Campaign Focus:** Allocate the majority of the 2017 advertising budget to the PS4 and Xbox One, as they are in the prime stages of their hardware life cycles.
*   **Marketing Assets:** Leverage professional critic scores and accolades in promotional materials (as they directly correlate with sales), and disregard user scores for marketing decisions.
*   **Regional Localization:** Tailor ad campaigns strictly by region. Focus on Action and Shooter titles for North American and European audiences, while dedicating the Japanese marketing budget heavily toward Handheld RPG titles.

## Repository Contents

*   `games_analysis.ipynb`: The main Jupyter Notebook containing the data exploration, statistical tests, and visualizations.
*   `datasets/`: Folder intended for the raw dataset (Note: `games.csv` is not included in this repository due to size constraints).

## How to Run the Project

1.  Clone this repository to your local machine.
2.  Ensure you have Python installed along with the required libraries (`pandas`, `numpy`, `matplotlib`, `seaborn`, `scipy`).
3.  Place the `games.csv` dataset in a local `datasets/` folder.
4.  Open `games_analysis.ipynb` in VS Code or Jupyter Notebook and run all cells.

---
This project was completed by Renan Henrique Duarte Ferreira as part of a Data Analytics curriculum.