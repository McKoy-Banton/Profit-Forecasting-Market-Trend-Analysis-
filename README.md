# Global Business Intelligence: Sales Analytics & Sentiment Analysis

## Project Overview
This project conducts comprehensive business intelligence analysis by combining global sales data with traveler sentiment analysis. The analysis identifies market trends, seasonal patterns, and develops a predictive model for profit forecasting to support data-driven investment decisions.

## Project Structure
├──Analysis.Rmd # Main R Markdown analysis file <br>
├──sales_data01.csv # Global sales dataset <br>
├──traveler_reviews.csv # Traveler reviews dataset <br>
└──README.md # Project documentation <br>

## Key Analyses Performed

### 📊 Sales Data Analytics
- **Data Engineering**: Cleaned and transformed 25,000+ records with missing value imputation and outlier treatment
- **Exploratory Analysis**: Regional performance, product category trends, and seasonal patterns
- **Predictive Modeling**: Linear regression for profit forecasting with 100% accuracy

### 💬 Sentiment Analysis
- **Text Mining**: NLP processing of traveler reviews for Thailand, Malaysia, and Japan
- **Sentiment Classification**: NRC lexicon-based sentiment scoring
- **Visualization**: Word clouds and comparative analysis across countries

## Technical Skills Demonstrated

### Programming & Tools
- **Language**: R
- **Libraries**: dplyr, ggplot2, tm, caret, wordcloud, syuzhet
- **Techniques**: Data wrangling, machine learning, NLP, data visualization

### Methodologies
- Data cleaning and preprocessing
- Statistical analysis and correlation studies
- Time series and seasonal trend analysis
- Predictive modeling and model evaluation

## Key Findings
- Identified highest-performing regions and product categories
- Discovered seasonal spending patterns for cosmetics and personal care
- Built accurate profit prediction model (RMSE: 5.81e-09)
- Determined positive dominant sentiment across all traveler reviews

## Usage
1. Open `analysis.Rmd` in RStudio
2. Ensure required datasets are in the working directory
3. Install necessary R packages
4. Knit the document to generate the complete analysis report

## Requirements
```r
install.packages(c("dplyr", "ggplot2", "tm", "caret", "wordcloud", 
                   "syuzhet", "RColorBrewer", "lubridate"))
