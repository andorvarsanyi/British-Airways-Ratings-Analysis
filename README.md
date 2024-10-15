# British Airways Customer Reviews Analysis

You can find the Tableau visualizations for this analysis [here](https://public.tableau.com/app/profile/andor.varsanyi5689/viz/BritishAirwaysReviews_17290336573510/Dashboard1).

## Introduction

This repository contains a Jupyter notebook that performs an in-depth analysis of British Airways customer reviews. The project aims to uncover insights into customer satisfaction, preferences, and trends across various aspects of the airline's service.

## Project Overview

The analysis covers multiple dimensions of customer reviews, including:

- Overall ratings distribution
- Recommendations analysis
- Seat type comparisons
- Traveller type preferences
- Route popularity
- Time-based trends
- Verified vs. non-verified trip comparisons

Through data visualization and statistical analysis, we explore patterns and correlations within the dataset to provide actionable insights for improving customer experience.

## Data Description

The dataset (`ba_reviews.csv`) contains customer reviews for British Airways flights. It includes the following key features:

- Rating
- Recommendation status
- Seat type
- Traveller type
- Route
- Date of review
- Various service aspect ratings (e.g., seat comfort, cabin staff service)

## Analysis Highlights

1. Distribution of ratings and recommendations
2. Average ratings by seat type and traveller type
3. Detailed seat type analysis using spider plots
4. Time series analysis of ratings
5. Top routes and departure places
6. Seat comfort analysis
7. Statistical tests (ANOVA) to compare ratings across seat types

## Key Findings

(Note: Actual findings would depend on the data analysis results. Here are some example findings:)

1. Business Class consistently receives higher ratings across all service aspects.
2. There's a slight positive correlation between flight distance and overall rating.
3. Verified trips tend to have higher ratings compared to non-verified trips.
4. Seasonal trends show higher satisfaction during summer months.
5. Seat comfort is the most significant factor influencing overall ratings.

## Setup Instructions

1. Clone this repository:
   ```
   git clone https://github.com/yourusername/ba-reviews-analysis.git
   ```

2. Ensure you have Python 3.7+ installed.

3. Install required packages:
   ```
   pip install -r requirements.txt
   ```

4. Place the `ba_reviews.csv` file in the project root directory.

## Usage Guidelines

1. Open the Jupyter notebook `ba_reviews_analysis.ipynb` using Jupyter Lab or Jupyter Notebook:
   ```
   jupyter lab
   ```
   or
   ```
   jupyter notebook
   ```

2. Run the cells in order to reproduce the analysis.

3. Feel free to modify the code or add new analyses as needed.

## Contributing

Contributions to improve the analysis or add new features are welcome. Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
