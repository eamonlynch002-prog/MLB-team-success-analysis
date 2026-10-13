# What Statistics Are Most Associated with MLB Team Success?

**Python Statistical Analysis | 2020–2025 MLB Seasons**

## Project Overview

This project investigates the relationship between three key baseball statistics—Batting Average (BA), On-Base Plus Slugging (OPS), and Earned Run Average (ERA)—and MLB team winning percentage.

Using team-level data from the 2020–2025 MLB seasons, we applied statistical analysis and regression techniques to examine which metrics had the strongest associations with team success.

## Research Question

Which of the three statistics—BA, OPS, or ERA—has the strongest relationship with MLB team winning percentage?

## Tools & Technologies

- **Python:** pandas, NumPy, Matplotlib, SciPy, statsmodels
- **Methods:** Ordinary Least Squares (OLS) regression, descriptive statistics, hypothesis testing, independent-samples t-test
- **Visualization:** Scatterplots, regression lines, and comparative bar charts

## Methodology

1. Imported and combined six seasons of MLB team statistics.
2. Prepared a dataset containing team, season, winning percentage, batting average, OPS, and ERA.
3. Fit separate OLS regression models to examine each statistic's relationship with winning percentage.
4. Created visualizations to interpret the statistical relationships.
5. Compared the winning percentages of teams with the lowest average ERAs.
6. Conducted an independent-samples t-test comparing winning percentages for lower-ERA and higher-ERA teams.

## Key Findings

- **ERA:** Demonstrated the strongest overall association with winning percentage among the three metrics examined. Teams with lower ERAs generally had higher winning percentages.
- **OPS:** Showed a stronger positive relationship with winning percentage than batting average.
- **Batting Average:** Showed a comparatively weaker positive relationship with winning percentage.
- **Hypothesis Testing:** The difference in winning percentage between lower-ERA and higher-ERA groups was statistically significant in the analysis.

These results highlight the importance of pitching performance while illustrating how quantitative methods can help investigate baseball-related questions.

## Project Files

- `Final_Presentation.ipynb` — Original Python analysis, regression models, visualizations, and statistical tests.
- `Analysis.pdf` — Research presentation summarizing the methods and findings.
- `2020.csv`–`2025.csv` — MLB team statistics used in the analysis.

## Limitations

This project examines statistical associations rather than establishing causation. The regression models were used to analyze relationships within the historical dataset; they were not evaluated using a separate out-of-sample test set. The findings should therefore not be interpreted as validated forecasts of future team performance.

## Contributors

**Eamon Lynch and Cole Goucher**

Collaborative MLB statistical research project. Eamon Lynch led the Python analysis, statistical modeling, and development of the research presentation.

## Data Sources

Historical MLB team statistics from Baseball-Reference, covering the 2020–2025 seasons.
