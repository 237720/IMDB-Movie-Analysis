📊 IMDB Movie Data Analysis Dashboard — End-to-End Project

-🚀 Project Overview

This project is an end-to-end Data Analytics pipeline built using Python, MySQL, Excel, and Power BI to perform Data Cleaning, Exploratory Data Analysis (EDA), and create an interactive business dashboard for IMDb Movie Data.

The goal of the project is to analyze movies based on various metrics such as Genres, Ratings, Revenues, Directors, and provide an interactive dashboard for stakeholders to explore the data dynamically.

-🗂️ Dataset Used

IMDB-Movie-Data.csv — 1000 popular movies with fields like Title, Genre, Director, Revenue, Rating, Votes, Metascore, etc.

Source: Kaggle - IMDB 1000 Movie Dataset

-🛠️ Tools & Technologies

Python (Pandas, Matplotlib, Seaborn)

MySQL (Database storage)

Excel (for initial exploration)

Power BI (Dashboard visualization)

HeidiSQL (for MySQL database management)

-🔄 Project Workflow

1.Data Collection

Downloaded the IMDB movie dataset from Kaggle.

2.Data Cleaning (Python)

-Handled null values, fixed column names.

-Transformed Genre into a list format and exploded multi-genre entries.

3.Exploratory Data Analysis (Python Seaborn & Matplotlib)

-Visualized trends like:

Movies Released per Year

Average Rating by Genre

Revenue vs Rating

Top Directors by Average Ratings

4.Database Storage (MySQL)

Created a database named imdb_analysis.

Stored the cleaned data into MySQL using Python .

5.Power BI Dashboard Creation

-Connected Power BI to MySQL Database.

-Developed a two-page dashboard:

Page 1: Overview Dashboard (Cards, Charts, Summary visuals)

Page 2: Detailed Data View (Interactive table with slicers)

-Applied Slicers (Genre, Director, Year, Rating, Revenue) synced across pages.

-Created dynamic visualizations:

Top 10 Genres by Movie Count

Top 5 Directors by Movie Count (Pie Chart)

Revenue and Rating Analysis

Interactive Table View with filtering.

📊 Power BI Dashboard Features

Fully Interactive Filters (Genre, Director, Year, Rating, Revenue)

Card Metrics: Total Movies, Average Ratings, Total Revenue, Total Votes.

Top Genres and Directors Visualization.

Detailed Movie Data Table with Conditional Formatting.

Sync Slicers across Pages for seamless filtering.
