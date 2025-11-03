# Movies Data Analysis

A comprehensive analysis of movie data using Python, exploring trends in genres, ratings, popularity, and release dates.

## Project Overview

This project analyzes a dataset of 9,827 movies to uncover insights about:
- Genre distribution and popularity
- Movie ratings and vote counts
- Release date trends
- Popularity metrics

## Dataset

The dataset (`MovieDB.csv`) contains the following features:
- **Release_Date**: Movie release year
- **Title**: Movie name
- **Popularity**: Popularity score
- **Vote_Count**: Number of votes
- **Vote_Average**: Average rating (categorized)
- **Genre**: Movie genre(s)

## Technologies Used

- **Python 3.x**
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical operations
- **Matplotlib**: Data visualization
- **Seaborn**: Statistical data visualization

## Key Findings

### Genre Distribution
- **Most common genre**: Drama (3,715 occurrences)
- Genres analyzed include Action, Adventure, Animation, Comedy, Crime, Drama, and more

### Movie Ratings
- Ratings categorized into: `not_popular`, `below_avg`, `average`, and `popular`
- Balanced distribution across rating categories

### Popularity Highlights
- **Highest popularity**: Spider-Man: No Way Home (5083.954)
- **Lowest popularity**: The United States vs. Billie Holiday & Threads (13.354)

### Release Date Trends
- Dataset spans from 1984 to 2022
- Peak movie releases in recent years

## Analysis Features

### Data Cleaning
- Removed unnecessary columns (Overview, Original_Language, Poster_Url)
- Converted Release_Date to year format
- Handled missing values
- Categorized Vote_Average into quartiles

### Data Transformation
- Exploded genre column for multi-genre movies
- Created categorical ratings based on vote averages
- No duplicate entries found

### Visualizations
- Genre distribution count plot
- Vote average distribution
- Release date histogram

## Project Structure
```
├── MoviesDataAnalysis.ipynb    # Main analysis notebook
├── MovieDB.csv                 # Dataset (not included in repo)
└── README.md                   # Project documentation
```

## Getting Started

### Prerequisites
```bash
pip install pandas numpy matplotlib seaborn
```

## Sample Statistics

- **Total Movies**: 9,827
- **Genres**: 19 unique categories
- **Date Range**: 1920s - 2022
- **Average Popularity**: 40.33
- **Average Vote Count**: 1,392.81
- **Average Rating**: 6.44

## License

This project is open source and available under the MIT License.

---
By Hamza Hibbah Falaki
