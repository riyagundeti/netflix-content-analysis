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

## Analysis 1: Movies vs TV Shows
6,131 Movies vs 2,676 TV Shows — movies make up about 70% of the catalog. Makes sense operationally: movies are one-off acquisitions, while TV shows need ongoing investment across seasons if they perform well.

## Analysis 2: Top 10 Countries by Content
The US leads by far, as expected. What stood out was India landing in the top 3 — ahead of several countries with bigger overall film industries. Points to Netflix specifically pushing regional/original content in India rather than just relying on the US catalog internationally.

## Analysis 3: Titles Added Over Time
Additions were slow until 2016, then spiked, peaking at 1,999 titles in 2019. Drops off after that — timing lines up with the pandemic hitting production, but this dataset doesn't actually prove that's the cause, just noting the overlap.

## Analysis 4: Top Genres
International Movies (2,752) and Dramas (2,427) are way ahead of everything else, including Comedies (1,674). Ties back to the country data — a catalog this drama- and international-heavy fits with Netflix's global content push rather than a US-centric library.

## Analysis 5: Content Maturity Trend Over Time
I Bucketed ratings into Kids/Teens/Adults and tracked the split by release year. Adult content went from ~32% to 50%+ of releases between 2008–2021, Teen content dropped from ~60% to ~35%. Kids' content barely moved — Netflix isn't dropping kids' shows, it's just adding adult content much faster.

---

## Key Takeaways

- Movies represent approximately 70% of Netflix's catalog.
- The United States remains the largest content producer, with India emerging as a major contributor.
- Netflix expanded its library aggressively between 2016 and 2019.
- International Movies and Dramas dominate the platform.
- Adult-oriented content has grown substantially faster than Kids' or Teen content.

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
