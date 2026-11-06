# Airbnb NYC Data Analysis

## Project Overview
This project analyzes the Airbnb New York City dataset using Python and Pandas. The objective is to understand Airbnb listing prices, room types, neighbourhood distribution, missing values, and other useful patterns.

## Dataset
- Dataset: AB_NYC_2019.csv
- Source: Kaggle – New York City Airbnb Open Data
- Format: CSV

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Visual Studio Code

## Project Tasks

### 1. Dataset Reading
Loaded the Airbnb NYC CSV dataset using Pandas.

### 2. Data Understanding
Explored the dataset using:
- head()
- shape
- info()
- describe()
- isnull().sum()

### 3. Data Transformation
- Removed unnecessary columns.
- Created a new price_category column.
- Organized listing prices into Budget, Moderate, Premium, and Luxury categories.

### 4. Missing Value Handling
- Used mean imputation for missing reviews_per_month values.
- Replaced missing listing names and host names with "Unknown".
- Verified the remaining missing values.

### 5. Insight Generation
Analyzed:
- Average Airbnb price.
- Room type distribution.
- Neighbourhood-wise listing counts.
- Average price by neighbourhood.
- Price category distribution.

### 6. Data Visualization
Created four visualizations:
1. Average Airbnb price by neighbourhood.
2. Airbnb room type distribution.
3. Number of Airbnb listings by neighbourhood.
4. Airbnb listings by price category.

## Key Findings
- Manhattan has the highest average listing price.
- Bronx has the lowest average listing price.
- Budget listings are the most common price category.
- Luxury listings are the least common price category.

## How to Run
1. Download or clone this repository.
2. Open the project folder in Visual Studio Code.
3. Install the required Python libraries:
   `pip install pandas numpy matplotlib seaborn jupyter`
4. Open `airbnb_analysis.ipynb`.
5. Select your Python kernel.
6. Run the notebook cells.

## Author
Student Python Fundamentals Challenge – CIE 1
