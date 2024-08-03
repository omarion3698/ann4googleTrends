# Author
Omar A. Hussein

## Overview

This project involves building and evaluating neural network models to predict the `query` variable in the Google Trends dataset based on `location`, `year`, `category`, and `rank`. 
Various network architectures with different hidden layer configurations were explored to determine the most effective model.

## Dataset

The dataset contains the following columns:
- `location`: The geographical location (e.g., Global, United States).
- `year`: The year the data was recorded.
- `category`: The category of the query (e.g., Consumer Brands, People).
- `rank`: The rank of the query in the given category and year.
- `query`: The search term or query.

## Model Architectures

Three neural network models were evaluated:
1. **Two hidden layers** with 4 and 2 neurons respectively.
2. **Three hidden layers** with 4, 6, and 2 neurons respectively.
3. **Ten hidden layers** with 4, 5, 10, 8, 20, 50, 10, 6, 40, and 2 neurons respectively.

## Installation

To run this project, ensure you have the following R packages installed:
  * neuralnet - Provides tools for training and evaluating customizable neural network models in R.
  * dplyr - Offers efficient functions for data manipulation and transformation using a consistent grammar of data operations.
  * tidyverse - A collection of R packages designed for data science, facilitating data import, tidying, transformation, visualization, and analysis.


## Cloning the Repository

To clone this repository, use the following command:
git clone https://github.com/omarion3698/ann4GoogleTrends.git

## Contact Information

If you have any questions or contributions, please email me at [omaribinbakarivic@gmail.com].

## License

License MIT: Copyright © 2024 Omar Hussein
