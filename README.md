# Credit_Risk_Analysis
## Overview
Credit risk is no easy task to predict. In this challenge we will take a closer look at our loan_stats csv to predict if someone is at low or high risk. The data will be transformed and 6 different and analyzed for 6 different machine learning models.  Jill asks us to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling. Below you will found the results. 


## Results
- Naive Random Oversampling Results:
![Screen Shot 2022-04-01 at 1 13 48 AM](https://user-images.githubusercontent.com/92552837/161199212-efad1085-5323-40db-ad61-ffab9e084434.png)


- Smote Oversampling Results:
![Screen Shot 2022-04-01 at 1 15 50 AM](https://user-images.githubusercontent.com/92552837/161199427-6ebf39d8-5f33-4ed6-ba52-45bb53d04e19.png)


-Undersampling Results:
![Screen Shot 2022-04-01 at 1 17 41 AM](https://user-images.githubusercontent.com/92552837/161199472-50ac762d-1f92-4918-bf74-34be2634329c.png)

-Combination(over and undersampling) results: 
![Screen Shot 2022-04-01 at 1 18 59 AM](https://user-images.githubusercontent.com/92552837/161199607-e3485c2e-1bdf-4c6a-be0e-9710ae4ddc3c.png)

-Balanced Random Forest Classifier results:
![Screen Shot 2022-04-01 at 1 20 25 AM](https://user-images.githubusercontent.com/92552837/161199764-af04a9e8-aa47-45ac-8a57-d333579bef77.png)

-Easy Ensemble AdaBoost Classifier results:
![Screen Shot 2022-04-01 at 1 21 09 AM](https://user-images.githubusercontent.com/92552837/161199820-8406a399-8d01-4be2-ae30-0f728efbe4a1.png)



## Summary
For the first 4 models we over sampled, undersampled and tried doing a combination of both in order to determine which is the best to predict loans at high risk. I recommend the ensemble classifiers over the first four models.
