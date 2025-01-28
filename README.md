# Netflix Movie Data Analysis

This project analyzes a dataset of Netflix movies using Python. The analysis involves cleaning, visualizing, and extracting insights from the data. The primary tools used are pandas, matplotlib, and seaborn.

## Dataset Overview
The dataset contains the following columns:
- **Title**: Title of the movie.
- **Genre**: The genre(s) of the movie.
- **Popularity**: Popularity score of the movie.
- **Vote_Count**: Number of votes received by the movie.
- **Vote_Average**: Average vote score of the movie.
- **Release_Date**: Release date of the movie (converted into year, month, and day).

## Questions Addressed
The analysis answers the following key questions:

1. **What is the most frequent genre in the dataset?**
   - A visualization highlights the most common genres in Netflix movies.

2. **Which movie has the highest popularity, and what is its genre?**
   - Insights into the most popular movie based on the dataset.

3. **Which movie has the lowest popularity, and what is its genre?**
   - Exploration of the least popular movie and its associated genre.

4. **Which year has the most movies released?**
   - A histogram visualizes the distribution of movie releases over the years.

## Data Cleaning and Transformation
The dataset was preprocessed with the following steps:
- Dropped irrelevant columns: `Overview`, `Poster_Url`, and `Release_Date`.
- Converted the `Release_Date` column into separate `Release_year`, `Release_month`, and `Release_date` columns.
- Split the `Genre` column into individual genres for better analysis.
- Removed duplicates and handled missing values.

## Visualization
The analysis includes visualizations to gain insights into the data, such as:
- Genre distribution using bar plots.
- Movie release year distribution using histograms.

## Tools and Libraries Used
- **pandas**: For data manipulation and cleaning.
- **numpy**: For numerical computations.
- **matplotlib**: For creating static visualizations.
- **seaborn**: For advanced and aesthetic data visualizations.

## Usage
To run the analysis, ensure you have the required libraries installed. Use the following commands to install them:

```bash
pip install pandas numpy matplotlib seaborn
```

Run the Python notebook in Jupyter Notebook or JupyterLab to reproduce the analysis and visualizations.

## License
This project is for educational purposes. Feel free to use and modify it as needed.
