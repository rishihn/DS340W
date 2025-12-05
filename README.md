# Utilizing a Weighted Ensemble Apporach to Increase House Price Prediction Accuracy
Using our parent paper's code and ideas shared from this paper and our other supplemental papers, we were able to create a more accurate and optimal model that can predict housing prices. Instead of relying solely on XGBoost likeour parent paper did, our sensemble combiens model prediction outputs from the following three models, each given a custom weight:
- XGBoost: (Weight = 0.8)
- Random Forest: (Weight = 0.1)
- Linear Regression: (Weight = 0.1)

To accomplish this, we utilized the finalized, clean dataset given to us by our parent paper and added onto the pre-existed code by implementing our ensemble model approach.

## "Datasets" Folder
- "AmesHousing.csv": Original Ames dataset obtained from Kaggle (https://www.kaggle.com/datasets/shashanknecrothapa/ames-housing-dataset), not used in our code
- "final.csv":  The finalized, cleaned Ames dataset used in our code

## "Code" Folder
This folder involves all the code orginating from our parent paper. It includes the code used to clean the "AmesHousing.csv" file, along with the code needed to run each model tested in the paper.

## "Our Code" Folder




## How to Run
titled "final.csv", which is found in the "Datasets" folder. Our novelty is found in the "Our Code" folder, which is titled "Weighted_Ensemble_vs_XGBoost". In this file, we leverage a weighted ensemble approach heavily inspired from our supplemental research papers to improve the model's accuracy. 
