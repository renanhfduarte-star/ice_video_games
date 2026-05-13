# 🎮 Video Game Market Analysis (Ice Online Store)

## 📌 Project Overview
This project analyzes historical video game sales data to identify patterns that determine a game's success. The goal is to provide data-driven recommendations for the 2017 advertising campaigns of "Ice", an international online video game store.

## 🛠️ Tools & Technologies
* **Python 3**
* **Pandas & NumPy:** Data cleaning, transformation, and aggregation.
* **Matplotlib & Seaborn:** Data visualization (boxplots, scatter plots, line charts).
* **SciPy:** Statistical hypothesis testing (Two-Sample t-test).
* **Jupyter Notebook:** Interactive data analysis.

## 📊 Key Business Insights
1. **Platform Life Cycle:** Gaming platforms typically have a 10-year life cycle. The strategy for 2017 should heavily focus on the PS4 and Xbox One.
2. **Review Impact:** A cross-platform analysis (PS4, Xbox One, PC, 3DS) confirmed a universal market rule: professional critic scores have a moderate positive correlation with commercial success. User scores, however, show almost zero correlation across all major consoles.
3. **Regional Differences:** 
   * The NA and EU markets are very similar (Action/Shooter games on Home Consoles).
   * The Japanese market is fundamentally different, dominated by Handheld consoles (Nintendo 3DS) and Role-Playing Games (RPG).

## 📂 How to Run
To run this project locally, you will need the `games.csv` dataset (not included in this repository due to size constraints). 
1. Clone this repository.
2. Place the dataset in a `/datasets/` folder.
3. Run the Jupyter Notebook `games_analysis.ipynb`.