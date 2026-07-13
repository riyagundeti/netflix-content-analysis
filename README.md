A data analysis project exploring Netflix's content library 
of 8800+ titles using Python and Pandas to uncover trends 
across countries, categories and ratings.

---

## Objective

To understand what kind of content Netflix produces, which 
countries dominate, and how the platform has grown over time 
using exploratory data analysis.

---

## Analyses Performed

### Analysis 1: Movies vs TV Shows
Netflix has 6131 Movies and 2676 TV Shows, meaning movies 
make up roughly 70% of all content on the platform.

### Analysis 2: Top 10 Countries
The United States dominates Netflix content production by 
a significant margin. India ranks in the top 3 globally, 
reflecting Netflix's heavy investment in Indian original content.

### Analysis 3: Titles Added Over Time
Additions stayed low until 2016, then surged, peaking in 2019 at 1,999 titles. Numbers declined after that, likely due to the pandemic and rising content costs.

### Analysis 4: Top 10 Genres
International Movies (2,752) and Dramas (2,427) lead by a wide margin, followed by Comedies (1,674). This reflects Netflix's focus on global, drama-heavy content over US-centric programming.

### Analysis 5: Content Maturity Trend Over Time

Tracked how Kids/Teens/Adults rating share changed by release year using a stacked area chart.
**Insight:** Adult-rated content share nearly doubled (32% → 50%+) from 2008–2021, while Teen content share fell (60% → 35%) — Netflix has skewed more mature over time.

---

## Tools Used
- Python 3
- Pandas
- Matplotlib for data visualization
- VS Code

---

## Dataset
- Source: Kaggle — Netflix Movies and TV Shows
- Size: 8807 titles, 12 columns

---
## Key Techniques

- Handling missing values
- Converting string dates into datetime objects for time-based analysis
- Splitting and exploding multi-value columns to analyze individual categories
- Building comparative visualizations (bar charts, line charts) to communicate trends

---

## How to Run
1. Clone this repository
2. Install requirements: pip install pandas matplotlib
3. Open the file in VS Code and run

---
## Future Scope

-Build a basic "what to watch next" suggestion based on genre and country overlap
-Dig deeper into India's content specifically, since it ranks in the top 3 globally
-Check if genre mix shifted during 2020–2021, when comfort-watching likely spiked

---

## About
Part of a self-directed data science learning journey.
