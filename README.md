# Utilizing a Weighted Ensemble Apporach to Increase House Price Prediction Accuracy
Using our parent paper's code and ideas shared from this paper and our other supplemental papers, we were able to create a more accurate and optimal model that can predict housing prices. Instead of relying solely on XGBoost likeour parent paper did, our sensemble combiens model prediction outputs from the following three models:
- XGBoost
- Random Forest
- Linear Regression


Each of these three models were assigned different custom weights:
- XGBoost: (0.8)
- Random Forest (0.1)
- Linear Regression (0.1)


<img width="256" height="28" alt="image" src="https://github.com/user-attachments/assets/b9f78236-bd8c-45c6-93ed-ff9582f370b0" />

To accomplish this, we utilized the finalized, clean dataset given to us by our parent paper titled "final.csv", which is found in the "Datasets" folder. Our novelty is found in the "Our Code" folder, which is titled "Weighted_Ensemble_vs_XGBoost". In this file, we leverage a weighted ensemble approach heavily inspired from our supplemental research papers to improve the model's accuracy. Our weighted ensemble approach specifically utilizes the following models: XGBoost, Random Forest, and Linear Regression.
