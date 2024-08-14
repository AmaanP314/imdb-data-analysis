# IMDb Top 250 Movies Data Analysis

## Project Overview

This project involves scraping data for the top 250 movies from IMDb using Scrapy and performing exploratory data analysis (EDA) on the collected data. The goal is to extract valuable insights from the dataset and present them through various visualizations.

## Table of Contents

- [Project Overview](#project-overview)
- [Data Collection](#data-collection)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Results](#results)
- [Technologies Used](#technologies-used)
- [How to Run](#how-to-run)
- [Contributing](#contributing)
- [Contact](#Contact)

## Data Collection

The data was collected by scraping the IMDb website using Scrapy. The scraper navigates through the top 250 movies list and collects the following information for each movie:
- Movie Name
- Release Year
- Duration
- Genres
- IMDb Rating
- Number of Ratings

## Exploratory Data Analysis

After collecting the data, the dataset was cleaned and analyzed using a Jupyter notebook. The following analyses were performed:

1. **Data Cleaning**: 
   - Converted the duration into a uniform time format.
   - Split multiple genres into individual rows to analyze them separately.

2. **Descriptive Statistics**:
   - Summary statistics for ratings, release years, and movie durations.

3. **Distribution Analysis**:
   - Histograms for IMDb ratings, movie durations, and release years.

4. **Genre Analysis**:
   - Frequency distribution of genres.
   - Analysis of genres with the highest average ratings.

5. **Correlation Analysis**:
   - Heatmap to show correlations between numeric variables.

6. **Genre Ratings vs Number of Ratings**:
   - Combined bar and line plot to show the average rating and number of ratings for frequent genres.

## Results

The analysis provided several insights, including:

- The most common genres among the top 250 movies.
- The distribution of IMDb ratings, with most movies rated between 8.0 and 9.0.
- The relationship between the number of ratings and the average rating for each genre.

## Technologies Used

- **Python**: For data analysis and visualization.
- **Scrapy**: For web scraping the IMDb data.
- **Pandas**: For data manipulation and analysis.
- **Seaborn & Matplotlib**: For creating visualizations.
- **Jupyter Notebook**: For interactive data analysis.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/imdb-top-250-analysis.git
2. Install the required packages:
   ```bash
   pip install -r requirements.txt
3. Run the Scrapy spider to collect data:
   ```bash
   cd imdb-top-250-analysis
   scrapy crawl imdb -o top_imdb_movies.csv
4. Open the Jupyter notebook to perform the analysis:
   ```bash
   jupyter notebook imdb-data-analysis.ipynb

## Contributing

- Contributions are welcome! If you have any suggestions or improvements, feel free to create a pull request.

## Contact

Amaan Poonawala - [GitHub](https://github.com/amaanp314) | [LinkedIn](https://www.linkedin.com/in/amaan-poonawala)

Feel free to reach out for any questions or feedback.



   
