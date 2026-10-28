# Netflix Movies & TV Shows: Data Analysis

An exploratory data analysis of the Netflix catalog using Python and pandas. The project cleans a real-world dataset of 8,807 titles and answers simple questions about what the catalog contains.

## Dataset

[Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows) on Kaggle (by shivamb).
- 8,807 titles and 12 columns
- Columns include type, title, director, cast, country, date added, release year, rating, duration, genres and description

## What I Did

1. **Loaded and inspected** the data (shape, data types, missing values)
2. **Cleaned the data**
   - Replaced missing `director` and `cast` values with "No Data"
   - Replaced missing `country` values with "Unknown" so that no country's count is inflated
   - Dropped the few remaining rows with a missing date, rating or duration (under 0.2% of the data)
   - Removed duplicate rows
3. **Explored the data** and visualised the results

## Key Findings

- **Movies make up about 70% of the catalog**, so Netflix has far more movies than TV shows.
- **2018 is the busiest release year**, with more titles than any other year in the dataset.
- **Director (2,634), country (831) and cast (825)** had the most missing values in the raw data.

## Tools Used

- Python
- pandas
- NumPy
- Jupyter Notebook (Kaggle)

## How to Run

1. Download `netflix-analysis.ipynb` from this repository.
2. Download the dataset from the Kaggle link above.
3. Open the notebook in Jupyter or Kaggle and update the file path in the `pd.read_csv(...)` line to point to the dataset.
4. Run all cells.

## Files

- `netflix-analysis.ipynb`: the full analysis with code, charts and written findings
- `README.md`: project overview

## About Me

I'm Shalin Nathan, a Data Science and AI student at IIT Jodhpur.
[LinkedIn](https://www.linkedin.com/in/shalin-nathan-789594298/) | [GitHub](https://github.com/Shalin0003)
