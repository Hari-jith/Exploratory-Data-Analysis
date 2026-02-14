# Google Play Store Exploratory Data Analysis (EDA)

## Project Overview
This project performs an in-depth exploratory data analysis on a cleaned Google Play Store dataset to understand the factors that influence app success. The analysis focuses on discovering meaningful patterns related to user behavior, product quality, and commercial performance using data-driven techniques.

The goal of this project is not only to visualize the data, but to derive actionable insights that can be useful for product teams, developers, and business stakeholders.

---

## Dataset Description
The dataset contains metadata of mobile applications available on the Google Play Store, including:

- App name  
- Category  
- Rating  
- Reviews  
- Size  
- Installs  
- Price  
- Type (Free/Paid)  
- Content rating  
- Genres  

Dataset Link: https://www.kaggle.com/datasets/harshvir04/cleaned-google-play-store-dataset


The dataset was cleaned and preprocessed before analysis to handle missing values, inconsistent formats, and anomalies.

---

## Data Cleaning & Preprocessing

Key steps performed:

### 1. Missing Values
- **Rating**: Filled using median to avoid bias from extreme values.

### 2. Duplicates
- Duplicate app entries were identified.
- Logical duplicates (same app with multiple versions) were preserved where meaningful.

### 3. Anomalies
- Detected cases where number of reviews exceeded installs.
- These were flagged for analytical caution.

---

## Key Questions Explored

This analysis focuses on business-relevant questions:

- Is there a rating threshold for success?
- Are large apps penalized or rewarded by users?
- What pricing range gives the best value-per-rating?
- Do paid apps perform better than free apps?
- Are there apps with suspicious review patterns?
- How strongly do ratings and installs influence each other?

---

## Visualizations Used

- Histograms for feature distributions  
- Boxplots (log-scaled) for installs vs ratings  
- Bar charts for aggregated comparisons  
- Line plots for trends  
- Correlation heatmap for numeric features  

All plots were created using **matplotlib and seaborn**.

---

## Key Insights

### 1. Ratings vs Installs
Apps with ratings below 3 stars rarely achieve high installs. Once an app crosses 3 stars, installs increase sharply. This shows that ratings act as a gate for success, not just a gradual booster.

### 2. App Size
Larger apps tend to receive higher ratings. This suggests that size reflects product maturity and feature richness, not poor optimization.

### 3. Pricing
Moderately priced apps provide the best value-per-rating. Extremely expensive apps do not necessarily receive higher ratings.

### 4. User Perception Matters Most
Ratings and reviews are stronger predictors of success than technical factors like size or category.

---

## Final Conclusion

This analysis demonstrates that user perception metrics play the most critical role in determining app success. While technical attributes such as size and price contribute to performance, they are secondary to user satisfaction. Apps that maintain high ratings unlock exponential growth potential, whereas poorly rated apps face strong limitations regardless of other factors.

---

## Tools & Technologies

- Python  
- pandas  
- numpy  
- matplotlib  
- seaborn  
- Jupyter Notebook  
