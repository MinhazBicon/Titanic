The sinking of the RMS Titanic is one of the most infamous shipwrecks in history.� On April 15, 1912, during her maiden voyage, the Titanic sank after colliding with an iceberg, killing 1502 out of 2224 passengers and crew. This sensational tragedy shocked the international community and led to better safety regulations for ships.
One of the reasons that the shipwreck led to such loss of life was that there were not enough lifeboats for the passengers and crew. Although there was some element of luck involved in surviving the sinking, some groups of people were more likely to survive than others, such as women, children, and the upper-class.
In this challenge, we ask you to complete the analysis of what sorts of people were likely to survive. In particular, we ask you to apply the tools of machine learning to predict which passengers survived the tragedy.

Data

The data has been split into two groups:
* training set (train.csv)
* test set (test.csv)

Data Analysis Part
* Data Visualization
* Data cleaning
* Data encoding(Categorical to Numerical)

Using Language
* Python

Using Library 
* Numpy 
* Pandas 
* Matplotlib
* Seaborn
* Scikit-learn (sklearn)




Algorithm and their evalution 

**For Mod_1 dataset**

|  NO  |   Algorithm Name   |   Type     | Highest accuracy | Precision for 0 | Precision for 1 | 
| :--- | :----------------- | :--------- | :--------------- | :-------------- | :-------------- | 
|  1   | Logistic Regresson | Classifier |      0.821       |     0.83        |      0.81       |
|  2   |       SVM          | Classifier |      0.815       |     0.82        |      0.82       |
|  3   |   SGDClassifier    | Classifier |      0.798       |     0.81        |      0.79       |
|  4   |   DecisionTree     | Classifier |      0.815       |     0.82        |      0.82       |
|  5   |   Random Forest    | Classifier |      0.815       |     0.85        |      0.77       |
|  6   |      XGBOOST       | Classifier |      0.832       |     0.84        |      0.81       |
