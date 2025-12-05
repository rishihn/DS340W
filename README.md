# Utilizing a Weighted Ensemble Approach to Increase House Price Prediction Accuracy
Using our parent paper's code and ideas shared from this paper and our other supplemental papers, we were able to create a more accurate and optimal model that can predict housing prices. Instead of relying solely on XGBoost like our parent paper did, our ensemble combines model prediction outputs from the following three models, each given a custom weight:
- XGBoost: (Weight = 0.8)
- Random Forest: (Weight = 0.1)
- Linear Regression: (Weight = 0.1)

To accomplish this, we utilized the finalized, clean dataset given to us by our parent paper and added onto the pre-existed code by implementing our ensemble model approach.

## Datasets Folder
- "AmesHousing.csv": Original Ames dataset obtained from Kaggle (https://www.kaggle.com/datasets/shashanknecrothapa/ames-housing-dataset), not used in our code
- "final.csv":  The finalized, cleaned Ames dataset used in our code

## Code Folder
This folder involves all the code originating  from our parent paper. It includes the code used to clean the "AmesHousing.csv" file, along with the code needed to run each model tested in the parent paper.

## Our Code Folder
This folder includes our novelty and contribution to this work, where we implement and compare the results of our weighted ensemble model to the sole model, XGBoost, used in the parent paper. 
- "Weighted_Ensemble_vs_XGBoost.ipynb": The finalized code including our ensemble approach along with the custom weights assigned to each model. This file also contains the results comparison and visualization comparison.


## How to Run
1. 
