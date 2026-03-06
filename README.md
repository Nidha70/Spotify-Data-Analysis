# Spotify-Data-Analysis

This project performs **Exploratory Data Analysis (EDA)** on Spotify music data to understand patterns in song popularity, audio features, release trends, and genres. The analysis uses Python libraries to clean, explore, and visualize the dataset.

# Project Objectives

- Explore Spotify track and artist datasets
- Identify the most and least popular songs
- Analyze relationships between audio features
- Study trends in song releases over time
- Understand genre-based patterns in popularity and duration
- Visualize insights using charts and statistical plots

# Dataset

The project uses two datasets:

**tracks.csv**
- Track name
- Artists
- Popularity
- Release date
- Duration
- Audio features (energy, loudness, acousticness, etc.)

**artists.csv**
- Artist ID
- Artist genres

# Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn

# Key Analysis Performed

- Checked missing values and dataset structure
- Found **top 10 most popular songs**
- Identified **least popular songs**
- Converted song duration from milliseconds to seconds
- Analyzed **correlation between audio features**
- Studied **songs released per year**
- Explored **relationship between loudness, energy, popularity, and acousticness**
- Merged track and artist datasets to analyze **genres**

# Visualizations

The project includes several visualizations such as:

- Correlation Heatmap
- Regression Plots
- Histogram of songs per year
- Song duration trends
- Genre popularity charts

# How to Run

1. Install required libraries

pip install numpy pandas matplotlib seaborn

2. Place the datasets (`tracks.csv` and `artists.csv`) in the project folder.

3. Run the Python notebook or script to reproduce the analysis.

# Summary

This project demonstrates how **data analysis and visualization techniques** can be used to uncover insights from Spotify music data, including popularity trends, audio feature relationships, and genre patterns.
