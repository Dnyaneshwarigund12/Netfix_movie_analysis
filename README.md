# 🎬 Movie Data Analysis

## 📌 Project Overview

This project focuses on analyzing a dataset of movies (including Netflix releases) to uncover insights about genres, popularity trends, ratings, and yearly releases. The workflow includes **data cleaning, preprocessing, categorization, and visualization** using Python libraries.

## 🚀 Features

* Data cleaning and preprocessing (handling missing values, dropping irrelevant columns).
* Extracting release years from dates.
* Splitting and exploding genres into individual categories.
* Categorizing movies by popularity levels based on average votes.
* Visualizing trends in movie genres, popularity, and yearly release patterns.

## 📊 Key Insights

* Most frequent movie genres on Netflix.
* Movies with the highest and lowest popularity scores.
* Distribution of vote averages across categories.
* Year-wise trends in the number of movies released.

## 🛠️ Tech Stack

* **Python**
* **Pandas** – data cleaning & preprocessing
* **NumPy** – numerical operations
* **Matplotlib** & **Seaborn** – data visualization
* **Statsmodels** – statistical analysis

## 📂 Project Workflow

1. **Data Cleaning**

   * Casted release date into datetime and extracted year.
   * Dropped irrelevant columns like *Overview*, *Original Language*, *Poster URL*.
   * Removed duplicates.

2. **Feature Engineering**

   * Categorized `vote_average` into buckets: Popular, Average, Below Average, Not Popular.
   * Split and exploded `Genre` column into multiple rows.

3. **Data Visualization & Analysis**

   * Genre distribution across movies.
   * Popularity vs. ratings insights.
   * Yearly movie production trends.

## 📌 How to Run

```bash
# Clone the repository
git clone https://github.com/yourusername/Movie-Data-Analysis.git

# Navigate to project directory
cd Movie-Data-Analysis

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook Movie_data_analysis.ipynb
```

## 📈 Example Visuals

* Genre distribution chart
* Yearly release trends
* Popularity vs vote averages

## 🤝 Contribution

Pull requests are welcome! If you find an issue, open a GitHub issue for discussion.
