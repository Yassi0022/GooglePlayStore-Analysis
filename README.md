#  Google Play Store App Analysis

This project analyzes data from the Google Play Store to understand user behavior, the most popular app categories, the differences between free and paid apps, and more.

##  Dataset
- Source: Public Google Play Store Dataset  
- Cleaned file: `googleplaystore_clean.csv`

##  Data Cleaning
- Removed duplicate entries  
- Excluded ratings > 5  
- Converted `Reviews`, `Installs`, and `Price` to numeric values  
- Converted the `Size` column (e.g., 10M → 10,000,000 bytes)  
- Handled `NaN` values using category-based imputation  

##  Analysis and Visualizations
### 1. Rating Distribution  
Shows how most apps are rated between 4 and 5 stars.

### 2. Most Common Categories  
Displays the top 10 categories with the highest number of apps.

### 3. Ratings Comparison: Free vs Paid Apps  
Boxplot analysis to explore if there are rating differences based on app type.

##  Tableau  
You can upload the `googleplaystore_clean.csv` file to Tableau to create:
- Interactive charts on Installs, Price, Ratings, etc.  
- Heatmaps of Category vs Rating  
- Detailed analysis by year or Android version

##  Project Structure
```
  GooglePlayStore-Analysis
├── googleplaystore_clean.csv
├── rating_distribution.png
├── top_categories.png
├── free_vs_paid_ratings.png
├── README.md
```

