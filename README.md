# House Price Prediction - Regression

This project is a Kaggle competition entry for predicting house prices in Ames, Iowa using machine learning techniques. The competition dataset includes 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa. The goal is to predict the final price of each home.
https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques
## Overview
This competition runs indefinitely with a rolling leaderboard. It's a great way for data science students and practitioners to test their skills in regression techniques and creative feature engineering.

## Description
**Start here if...**
- You have some experience with R or Python and machine learning basics.
- You are looking to expand your skill set before trying a featured competition.

### Competition Description
Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. But this dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence.

With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home.

### Practice Skills
- Creative feature engineering 
- Advanced regression techniques like random forest and gradient boosting

### Acknowledgments
The Ames Housing dataset was compiled by Dean De Cock for use in data science education. It's an incredible alternative for data scientists looking for a modernized and expanded version of the often cited Boston Housing dataset.

Photo by Tom Thain on Unsplash.

## Evaluation
**Goal:**  
Predict the sales price for each house. For each Id in the test set, predict the value of the SalePrice variable.

**Metric:**  
Submissions are evaluated on Root-Mean-Squared-Error (RMSE) between the logarithm of the predicted value and the logarithm of the observed sales price. Taking logs means that errors in predicting expensive houses and cheap houses will affect the result equally.

**Submission File Format:**  
The file should contain a header and have the following format:




You can download an example submission file (`sample_submission.csv`) on the Data page of the competition.

## Getting Started
To get started quickly, you can use the starter notebook provided [here](https://www.kaggle.com/code/omerfarukaytunc/housepricepredict-regression).

## Repository Structure
- `data/`: Contains the dataset used for training and testing.
- `notebooks/`: Jupyter notebooks for data analysis, feature engineering, and model training.
- `models/`: Saved models and model predictions.
- `submissions/`: Submission files ready for Kaggle upload.
- `README.md`: Project overview and instructions.

## Usage
1. Clone the repository:
    ```bash
    git clone https://github.com/omrfrkaytnc/house-price-prediction.git
    cd house-price-prediction
    ```
2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the Jupyter notebook to train the model and make predictions:
    ```bash
    jupyter notebook notebooks/house_price_prediction.ipynb
    ```
4. Generate the submission file and upload it to Kaggle.

## Author
- Ömer Faruk Aytunç

For more details and the complete notebook, visit the [Kaggle Notebook](https://www.kaggle.com/code/omerfarukaytunc/housepricepredict-regression).

## License
This project is licensed under the MIT License - see the LICENSE file for details.

   
