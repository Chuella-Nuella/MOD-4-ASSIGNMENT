README for Netflix Data Analysis Assignment (BAN6420)

Overview

 The goal of this project is to analyze Netflix shows and movies data using Python and R for various tasks, including data preparation, cleaning, exploration, and visualization.
Steps and Workflow
•	Data Preparation:
Objective: Unzip the dataset and rename it to Netflix_shows_movies.csv.
Process:
The dataset is unzipped using Python's zipfile module, then the file is renamed for clarity and consistency.
•	Data Cleaning:
Objective: Address missing values and prepare the dataset.
Process:
Rows with missing values are removed, and columns are renamed for better readability (listed_in → genres). The date added column is converted to a proper date format. A clean version of the dataset is saved as Clean_Data_Set.csv.
•	 Data Exploration
Objective: Gain insights from the dataset through descriptive statistics and analysis.
Process:
Basic information about the dataset is displayed (e.g., data types, column names), then the summary statistics of categorical data are provided. Mode (most frequent values) for key columns (genres, title) is calculated.
•	 Data Visualization
Objective: Create insightful visualizations using Python.
Visualizations:
1. Most Watched Genres: A bar chart representing the top 10 most-watched genres.
Saved as Python_genre_most_watched.png.
2. Ratings Distribution:  A histogram showing the distribution of ratings.
Saved as Python_Rating_Distribution.png.

•	 Error Handling
Comprehensive error handling is implemented throughout the project to ensure robustness and provide meaningful error messages.

How to Use the Code

1. Prerequisites:
Python 3.x installed on your system.
Required Python libraries:
pandas
os
zipfile
seaborn
matplotlib
The dataset file netflix_data.zip is placed in the same directory as the script.

2. Steps to Run:
Run the Python script step by step in a Jupyter Notebook or an IDE, ensure that all dependencies are installed before executing the script.
Pip installs pandas seaborn matplotlib. Ensure the netflix_data.zip file is present in the working directory.
  3. Outputs:
Cleaned Dataset: Saved as Clean_Data_Set.csv.
Visualizations: Python_genre_most_watched.png: Bar chart of the most-watched genres.
Python_Rating_Distribution.png: Histogram of the rating distribution.






File Structure

BAN 6420 ASSIGNMENT MOD 4
├── netflix_data.zip                 # Original zipped dataset
├── Netflix_shows_movies.csv         # Renamed and unzipped dataset
├── Clean_Data_Set.csv               # Cleaned dataset
├── Python_genre_most_watched.png    # Genre visualization
├── Python_Rating_Distribution.png   # Ratings visualization
├── README.md                        # Instructions for the project
├── Netflix_Data_Analysis.py         # Python script for analysis


•	Error Handling
The script includes exception handling to ensure smooth execution and meaningful error messages in case of issues.

Example: 
 File not found.
Data type conversion errors.
