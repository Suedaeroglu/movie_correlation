
# Movies Data Analysis in Python

## Overview

This project explores a movies dataset using Python to extract insights and identify correlations between various movie features such as budget, gross revenue, genre, and ratings. The analysis provides valuable information, such as which factors are most influential in determining box office success, and highlights the relationships between key features through visualizations like scatter plots and heatmaps.

## Dataset

The dataset includes:

- Name: The title of the movie.

- Rating: The film's MPAA rating (e.g., PG, R).

- Genre: The genre classification (e.g., Action, Comedy).

- Year: The year the movie was released.

- Released: The exact release date of the movie.

- Score: IMDb rating.

- Votes: The number of user ratings on IMDb.

- Director: The person who directed the film.

- Writer: The screenwriter(s) for the film.

- Star: Lead actors/actresses.

- Country: The production country.

- Budget: Estimated production cost.

- Gross: Box office earnings.

- Runtime: Duration of the movie in minutes.

## Analysis Steps

Here are some of the key steps performed in the analysis:

- Import Libraries: Imported the necessary Python libraries such as Pandas, NumPy, Seaborn, and Matplotlib for data manipulation and visualization.

- Read in the Data: Loaded the dataset from a CSV file into a Pandas DataFrame.

- Spying for Missing Data: Identified and handled missing data by checking for null values in key columns like budget and gross revenue.

- Data Types for Columns: Verified and adjusted the data types of columns to ensure compatibility for numerical analysis.

- Drop Any Duplicates: Removed any duplicate entries to avoid skewing the analysis results.

- Budget High Correlation: Analyzed how movie budgets correlate with other variables, particularly gross revenue, to determine if higher-budget films tend to perform better at the box office.

- Company High Correlation: Investigated the relationship between the production companies and the movie's gross revenue, identifying companies that frequently produce successful movies.

- Scatter Plot with Budget vs Gross: Created scatter plots to visualize the direct relationship between a movie's budget and its box office earnings. This step also highlighted outliers such as high-grossing low-budget films.

- Plot Budget vs Gross Using Seaborn: Used the Seaborn library to create a more detailed and visually appealing plot of budget vs. gross, adding regression lines to see trends more clearly.

## Visualizations

- Correlation Heatmap: Displayed a heatmap showing correlations between numerical features such as budget, gross revenue, votes, and IMDb score. The heatmap revealed strong correlations between budget and gross revenue, indicating a direct relationship.

<img width="931" alt="Screenshot 2024-09-21 at 11 13 03" src="https://github.com/user-attachments/assets/5dabf8f6-16ca-4c10-8cc9-c806b96c6d53">


- Scatter Plot of Budget vs. Gross: Visualized how movie budgets relate to gross revenue. The scatter plot shows that higher-budget films generally earn more, but some low-budget films can become massive hits.

<img width="944" alt="Screenshot 2024-09-21 at 11 12 33" src="https://github.com/user-attachments/assets/a6d9b162-947a-4155-b97a-539444de1b85">


## Tools and Libraries

- Python: Used for performing data manipulation and analysis.

- Pandas: For handling and cleaning the dataset.

- Seaborn and Matplotlib: To create visualizations such as scatter plots, correlation matrices, and more.

- NumPy: Used for numerical computations.

- Jupyter Notebook: Environment for conducting and documenting the analysis interactively.

## Conclusion

This analysis provides insights into what factors contribute most to a movie's success at the box office, particularly the strong relationship between a movie’s budget and its gross revenue. Other elements, such as genre and director, also play a role. By analyzing these trends, one can better predict movie performance and make data-driven decisions in the film industry.

