# IMDB Top 1000 Movies Analysis

A comprehensive data analysis project examining the top 1000 movies from IMDB, exploring relationships between ratings, genres, revenue, and release years.

## 📊 Project Overview

This project analyzes the IMDB Top 1000 movies dataset to uncover insights about movie ratings, genres, box office performance, and critical reception. The analysis includes data cleaning, exploratory data analysis, and correlation studies.

## 📁 Dataset

**File**: `imdb_top_1000.csv`

The dataset contains information about 1000 top-rated movies from IMDB, including:
- Movie title and release year
- IMDB rating and Meta score
- Genre and certificate (rating)
- Director information
- Gross revenue
- And more...

## 🔍 Analysis Performed

### 1. Data Cleaning
- Handled missing values in `Certificate`, `Meta_score`, and `Gross` columns
- Cleaned `Released_Year` column by extracting numeric values
- Simplified `Genre` by keeping only the primary genre
- Converted `Gross` revenue to numeric format

### 2. Exploratory Analysis
- **Genre Analysis**: Average IMDB ratings across different genres
- **Top Movies**: Identified the top 10 highest-rated movies
- **Correlation Studies**:
  - Meta score vs IMDB rating
  - Gross revenue vs IMDB rating
- **Temporal Analysis**: Distribution of movies by release year

## 🛠️ Requirements

- Python 3.x
- pandas
- numpy

## 🚀 Getting Started

1. **Clone or download this repository**

2. **Install required packages**:
   ```bash
   pip install pandas numpy
   ```

3. **Open the Jupyter notebook**:
   ```bash
   jupyter notebook movie_rating.ipynb
   ```

4. **Run the cells sequentially** to perform the analysis

## 📈 Key Insights

The analysis provides answers to questions such as:
- Which genres have the highest average ratings?
- What are the top-rated movies in the dataset?
- How do critic scores (Meta score) correlate with audience ratings (IMDB)?
- Does higher gross revenue correlate with higher ratings?
- How is the distribution of movies across different years?

## 📝 Files Structure

```
├── imdb_top_1000.csv       # Dataset file
├── movie_rating.ipynb      # Jupyter notebook with analysis
└── README.md               # Project documentation
```

## 📧 Usage

This project is ideal for:
- Learning data cleaning and preprocessing techniques
- Understanding correlation analysis
- Practicing pandas and numpy operations
- Exploring movie industry trends

---

**Note**: Make sure the CSV file is in the same directory as the notebook before running the analysis.
