# Movie Data Analysis
## Overview
This project explores and analyzes a Movie Dataset using Python (Pandas, Numpy, Matplotlib, Seaborn).
The goal is to understand the relationships between different features (budget, gross revenue, votes, ratings, etc.) and to identify which factors contribute most to a movie's success.

---

## Steps in the Analysis
1. **Data Transformation & Cleaning**
   - Loaded the dataset using Pandas.
   - Converted categorical columns into numeric.

2. **Exploratory Data Analysis (EDA)**
   - Sorted movies by gross revenue to find the top-performing films.
   - Created scatter plots & regression plots:
   - Budget vs Gross - Built correlation matrices (Pearson & Spearman) - Visualized correlations with heatmaps.

3. **Key Insights**
   - Strong positive correlation between Budget and Gross Revenue.
   - Strong positive correlation between Votes and Gross Revenue.
   - Moderate correlation between Year and Gross Revenue (suggesting more recent movies tend to gross more).
   - Weak correlation between Score (IMDB rating) and Gross Revenue.

## Visualizations:
   - Scatterplot: Budget vs Gross.
   - Regression Plot: Budget vs Gross with trend line.
   - Heatmap: Correlation between numeric features.
   - Bar Chart: Top 15 companies by gross revenue.
