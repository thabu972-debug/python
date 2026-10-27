# ANIME DATA ANALYSIS AND VISUALIZATION

## Project Overview

This project explores an anime dataset using Python and data
visualization libraries. It analyzes anime types, ratings, episode
counts, and member counts to understand patterns in the dataset through
charts and summary statistics.

## Objectives

-   Explore and understand the anime dataset.
-   Inspect dataset structure, summary statistics, and missing values.
-   Analyze ratings across anime types.
-   Compare episode counts, ratings, and member counts.
-   Create visualizations to communicate findings clearly.

## Tools and Technologies

-   **Python** --- data analysis and visualization scripting
-   **Pandas** --- data loading, cleaning, and analysis
-   **NumPy** --- numerical operations
-   **Matplotlib** --- chart creation and layout
-   **Seaborn** --- statistical data visualization
-   **Jupyter Notebook** --- interactive analysis environment

## Dataset

The notebook loads a CSV file named `anime.csv`.

Columns used in the notebook include: - `type` --- anime format/type -
`rating` --- anime rating - `episodes` --- number of episodes -
`members` --- member count - `name` --- anime title (used in a chart)

Make sure `anime.csv` is available in the same folder as the notebook.
Column names may vary depending on the dataset version.

## Analysis and Visualizations

The notebook includes data inspection and visualizations such as: -
Anime count by type - Anime distribution by type (pie chart) - Rating
distribution (histogram and KDE) - Episodes versus rating (line and
scatter plots) - Rating comparison by anime type (box and violin
plots) - Anime member counts and comparisons - Pair plots to compare
numerical variables - Top-rated anime and anime with the most members

## Getting Started

### 1. Clone or download the repository

``` bash
git clone <your-repository-url>
cd <your-project-folder>
```

### 2. Install dependencies

``` bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 3. Add the dataset

Place `anime.csv` in the project folder alongside `project(1).ipynb` (or
rename the notebook to `anime_data_analysis.ipynb`).

### 4. Run the notebook

``` bash
jupyter notebook
```

Open the notebook and run the cells from top to bottom.

## Project Structure

``` text
anime-data-analysis/
├── anime.csv
├── anime_data_analysis.ipynb
└── README.md
```

## Key Learning Outcomes

-   Reading CSV data with Pandas
-   Inspecting columns, data types, and summary statistics
-   Identifying missing values and converting columns to numeric values
-   Grouping and aggregating data
-   Creating statistical and categorical visualizations
-   Organizing multiple charts for exploratory data analysis

## Future Improvements

-   Add a concise summary of the main findings.
-   Improve missing-value and duplicate handling.
-   Add interactive visualizations or a dashboard.
-   Compare ratings and popularity across anime types.
-   Include dataset source and licensing information.

## Author

Tabrez H

## Note

This repository contains an exploratory data analysis project. Findings
depend on the dataset used. Verify the dataset's source and column
definitions before drawing conclusions.
