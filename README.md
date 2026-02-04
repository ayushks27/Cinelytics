Cinelytics: Budget, Popularity & Revenue Insights
Overview

This project performs large-scale exploratory data analysis on a real-world movie dataset sourced from TMDb, containing metadata for over 10,000 films including budget, revenue, popularity, runtime, genre, and audience engagement metrics.
The goal is to uncover data-driven relationships between production attributes and commercial outcomes.

Business Questions Addressed

Does higher production budget correlate with higher popularity?

How does runtime influence popularity and audience engagement?

Does higher popularity translate into higher profits?

What attributes are common among the top-grossing movies?

How do genre popularity and revenue trends evolve over time?

Dataset Characteristics

10,000+ records spanning multiple decades

Mixed data types including numerical, categorical, and multi-value fields

Inflation-adjusted budget and revenue fields for fair temporal comparison

Real-world data challenges such as missing values, duplicates, and zero budgets

Data Preparation & Processing

Removed duplicate records and non-analytical fields

Handled missing categorical values using placeholder strategies

Converted invalid zero budgets to nulls for accurate aggregation

Parsed multi-value genre fields for time-series and group analysis

Engineered derived metrics including profit and budget tiers

Analytical Techniques

Correlation analysis between budget, popularity, revenue, and profit

Segmentation using median-based thresholds for comparative analysis

Time-series aggregation across genres and release years

Visualization using scatter plots, bar charts, histograms, and heatmaps

Feature-level comparison for top revenue-generating movies

Key Insights

Higher budgets are associated with significantly higher average popularity, though not guaranteed success

Movies with moderate runtimes outperform very short or excessively long films

Popularity strongly correlates with higher average profit

Top-grossing movies share common traits across runtime, budget scale, and release periods

Drama, Comedy, and Action dominate popularity and revenue trends over time

Limitations

Popularity and vote metrics are platform-defined and opaque

Incomplete budget data and currency inconsistencies affect precision

External factors such as marketing spend and regional performance are not captured

Tech Stack

Python

Pandas, NumPy

Matplotlib, Seaborn

Use Cases

Data exploration and validation pipelines

Business insight generation from large structured datasets

Feature analysis for downstream predictive modeling

Dataset
- The TMDb movie data (cleaned from original data on Kaggle).
- This data set contains information about 10,000 movies collected from The Movie Database (TMDb), including user ratings and revenue.

Libraries : 
- All the codes are written on Jupyternotebook. The python libraries include numpy, pandas, matplotlib and seaborn. Please make sure you have all these libraries installed. 
