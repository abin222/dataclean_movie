# Movie Data Analysis and Cleaning

This repository contains resources for cleaning and analyzing movie-related datasets. It includes a Jupyter Notebook for data preprocessing and two datasets: one with movie information and another with user ratings.

## Contents

### Files
1. **`Movie Data - Data Cleaning.ipynb`**  
   A Jupyter Notebook containing the steps for cleaning, preprocessing, and exploring movie-related data.

2. **`movies.csv`**  
   A dataset containing information about movies, such as:
   - Movie ID
   - Title
   - Genre(s)
   - Release Year

3. **`ratings.csv`**  
   A dataset with user rating information, including:
   - User ID
   - Movie ID
   - Rating
   - Timestamp

## Usage

### Running the Notebook
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/abin222/dataclean_movie
   ```
2. Navigate to the main project directory:
   ```bash
   cd dataclean_movie
   ```
3. Open the notebook in Jupyter Notebook or JupyterLab:
   ```bash
   jupyter notebook "Movie Data - Data Cleaning.ipynb"
   ```
4. Execute the cells sequentially to:
   - Load and preview the datasets.
   - Clean the data (e.g., handle missing values, remove duplicates).
   - Perform exploratory data analysis (EDA) if applicable.

### Data Sources
- **Movies Dataset (`movies.csv`)**: Provides details about movies, including genres and release years.
- **Ratings Dataset (`ratings.csv`)**: Contains user ratings for the movies.

## Project Objectives
- Clean and preprocess raw datasets for accurate analysis.
- Explore relationships within the movie data, such as trends in ratings or popular genres.
- Provide a foundation for further analysis, such as recommendation systems or predictive modeling.

## Example Output

### Sample Data Cleaning
- **Missing Data Handling**: Rows with missing movie titles or ratings are removed.
- **Duplicates Removal**: Duplicate rows in both datasets are dropped.
- **Data Standardization**: Genres and titles are standardized for consistency.

### Exploratory Data Analysis
- Identify the most popular movie genres.
- Analyze the distribution of user ratings.
- Explore trends in movie release years and their corresponding average ratings.

## Contributing
We welcome contributions! To contribute:
1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature description"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.
```
