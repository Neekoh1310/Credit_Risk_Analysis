# Credit_Risk_Analysis

## Overview

In this project, I was tasked to analyze credit risk using unbalanced methods. Since good loans easily outnumber risky loands, different techniques must be employed to train and evaluate models. I am going to employ Random Oversampling, SMOTE Oversampling, Undersampling, Combination Sampling, Balanced Random Forest Classifier Sampling, and Easy Ensemble Classifier Sampling to see what method will be most effective in analyzing credit risks.

## Resources
- Python, Jupyter Notebook, Pandas, Imbalanced Learn (imblearn)

## Results

<h3><b>Random Oversampling</b></h3>
- Balanced Accuracy: 0.7905209680473468 | Precision: 0.99 | Recall: 0.86

![Naive Random Oversampling](https://user-images.githubusercontent.com/102476861/179847554-740582e2-4ffa-448a-9b84-97e907bcbc21.png)
____________________________

<h3><b>SMOTE Oversampling</b></h3>
- Balanced Accuracy: 0.7905209680473468 | Precision: 0.99 | Recall: 0.88

![SMOTE Oversampling](https://user-images.githubusercontent.com/102476861/179847586-a3c13c5d-baae-43a4-abe4-dffdbe7e228b.png)
____________________________

<h3><b>Undersampling</b></h3>
- Balanced Accuracy: 0.7905209680473468 | Precision: 0.99 | Recall: 0.88

![Undersampling](https://user-images.githubusercontent.com/102476861/179847614-0b998a6a-6e49-4490-a7dd-3babb736d58c.png)
____________________________

<h3><b>Combination Sampling</b></h3>
- Balanced Accuracy: 0.7905209680473468 | Precision: 0.99 | Recall: 0.88

![Combination Sampling](https://user-images.githubusercontent.com/102476861/179847638-65eaa06b-ddc5-4fd0-8b9a-de12df0fe6d9.png)
____________________________

<h3><b>Balanced Random Forest Classifier</b></h3>
- Balanced Accuracy: 0.7983711439057899 | Precision: 0.99 | Recall: 0.88

![Balanced Random Forest Classifier](https://user-images.githubusercontent.com/102476861/179847652-0b0d8a04-a843-417e-ab09-4836a1027bf6.png)
____________________________

<h3><b>Easy Ensemble AdaBoost Classifier</b></h3>
- Balanced Accuracy: 0.9263620468069506 | Precision: 0.99 | Recall: 0.94

![Easy Ensemble AdaBoost Classifier](https://user-images.githubusercontent.com/102476861/179847680-91314614-772e-4933-bbe0-3d697740c543.png)
____________________________

## Summary
Based on the balanced accuracy, precision, and recall scores on the methods that were run, the Easy Ensemble AdaBoost Classifier is the top recommendation. The other five methods produced an accuracy of <80%, with each only having a small margin of differences when it comes to precision and recalls, while Easy Ensemble produced an accuracy close to 93%. If 93% accuracy is acceptable within the business parameters of a Credit Risk company, then Easy Ensemble AdaBoost Classifier is highly recommended.



