# DATA 555: Music and Mental Health Visualizations

## Project Overview
This project explores the relationship between music listening habits and mental health conditions using the **"Music & Mental Health" dataset** from Kaggle. The dataset provides insights into how music influences stress, mood, and well-being.

## Dataset Information
- **Source:** [Kaggle Dataset](https://www.kaggle.com/datasets/catherinerasgaitis/mxmh-survey-results)
- **Collected by:** Catherine Rasgaitis
- **Collection Period:** August 2022 - November 2022
- **Final Sample Size (after cleaning):** 605 respondents

## Research Questions
1. Are mental health conditions improved by listening to music?
2. How do mental health disorder rankings vary across age groups?
3. Does the number of daily music listening hours vary based on anxiety and depression severity?

## Data Processing Steps
1. **Variable Renaming:** Standardized column names for clarity.
2. **Missing Data Handling:** Removed null values.
3. **Outlier Removal:** Excluded unrealistic values (e.g., extreme BPM values, incorrect mental health scores).
4. **Age Grouping:** Created categorized age groups.
5. **Data Transformation:** Rounded mental health scores for analysis.

## Required R Packages
Ensure the following libraries are installed before running the analysis:
```r
install.packages(c("dplyr", "tidyr", "ggplot2", "reshape2", "plotly", "DT", "flexdashboard", "viridis"))
```

## Importance and Real-World Impact
- This project can provide valuable information on how music listening habits are associated with self-reported mental health conditions. 
- Findings could inform public health initiatives by identifying specific music-related behaviors linked to better or worse mental health outcomes, potentially guiding music therapy applications and mental health interventions.

