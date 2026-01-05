# Project01_Linux_Movie

A Python-based data analysis tool designed to process and extract insights from the TMDb movie dataset (`tmdb-movies.csv`). This project demonstrates file handling, data sorting, filtering, and statistical analysis.

## 🚀 Overview
This application reads raw movie data and performs several analytical operations to answer key questions about the movie industry, such as identifying the most profitable movies or analyzing genre popularity.

## 📂 Project Structure
```text
├── NguyenNguyenHieu_K21_LV1_project_01.txt  # Main Source Code
├── tmdb-movies.csv                          # Input Dataset
├── README.md                                # Project Documentation
├── genre_statistic.txt                      # Output: Genre frequency analysis
├── movies_rating_above_7_5.csv              # Output: High-rated movies
├── movies_sorted_by_date.csv                # Output: Chronological movie list
└── top10_profit_movies.csv                  # Output: Highest-grossing movies
```

## ✨ Features
The application processes the tmdb-movies.csv file and generates the following reports:

1. Genre Statistics (genre_statistic.txt):
  - Analyzes the frequency of different movie genres within the dataset.

2. High Rating Filter (movies_rating_above_7_5.csv):
  - Filters and exports a list of movies with an average rating greater than 7.5.

3. Chronological Sorting (movies_sorted_by_date.csv):
  - Sorts all movies based on their release date (from newest to oldest or vice versa).

4. Top Profit Analysis (top10_profit_movies.csv):
  - Calculates profit (Revenue - Budget) and identifies the top 10 most profitable movies of all time.

## 🛠 Prerequisites
- Python 3.x.
- No external libraries are required (Pure Python implementation) [Or update this if you use pandas/numpy].

## 💻 Usage
1. Ensure tmdb-movies.csv is in the same directory as the script.

2. Run the Python script:
```bash
python NguyenNguyenHieu_K21_LV1_project_01.txt
```

3. Check the generated output files in the current folder for results.

## 📊 Data Source
- Dataset: TMDb Movie Metadata
- File: tmdb-movies.csv
