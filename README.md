# ieee-fraud-detection
Kaggle Competition: IEEE-CIS Fraud Detection
"In this competition you are predicting the probability that an online transaction is fraudulent, as denoted by the binary target isFraud.Submissions are evaluated on area under the ROC curve between the predicted probability and the observed target." 

(more info: https://www.kaggle.com/c/ieee-fraud-detection/data)

# Overall result
Ranked 244th/6,381 in Private Leaderboard with ROC = 0.928877.

# Methods
*Credits: I used this kernel https://www.kaggle.com/krishonaveen/xtreme-boost-and-feature-engineering as a base for data cleaning,  feature enegineering

-Feature engineering: Mostly frequency encoding, mean and median encoding of "Card-X" and V features.

-Models: XGBoost GPU with 5 Folds for cross validation

-Blending my result with other popular kernels using GMEAN (using this kernel as a guidelines: https://www.kaggle.com/kernels/scriptcontent/19932553/download)

