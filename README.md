# Credit_card
 This is a classification machine learning problem to detect fraudulent purshases.<br>
 This code is heavly based on the code made by janiobachmann from kaggle, if you want a more in depth explanation, please go to his notebook,<br>
 my objective here is to learn from janiobachmann and others to solve this problem and them apply the earned skills and methodology on another dataset.
## Challenges
This is a very clean dataset, however it has a very uneven amount of fraudulent and non fraudulent data and this can very easly skew the algorithm
## Code and Resources Used 
**Python Version:** 3.9  <br>
**Packages:** ipykernel,pandas,numpy,sklearn, matplotlib, seaborn <br>
**Requirements:**  ```pip install -r requirements.txt```  <br>
**Data Frame Credit card** https://www.kaggle.com/mlg-ulb/creditcardfraud
**Data Frame heart disease**https://www.kaggle.com/ronitf/heart-disease-uci
**Support jupternotebook**https://www.kaggle.com/janiobachmann/credit-fraud-dealing-with-imbalanced-datasets


## Heart_data_analysis.ipynb
Contains a data analysis based on janiobachmann jupyter notebook but on heart.csv data about heart disease<br>
We analyse the data distribution and how it correlates with the target and made changes when deemed necessary.
![alt text](https://github.com/chirlgava/Credit_card/blob/main/figures/correlation.png)<br>
From the picture above we learned the variables that are more likely to influence our data like: ['cp','thalach','slope'] (positive correlation) <br>
and ['exang','oldpeak','ca'] (negative correlation)

## Heart_data_ml
Contains a machine learning approach to classify heart disease with the given data <br>
We used 4 types of classifier to predict data: 
<ol>
<li>Logistic Regression:  0.9999157894736842</li>
<li>KNears Neighbors:  0.996</li>
<li>Support Vector Classifier:  1.0</li>
<li>Decision Tree Classifier:  0.996</li>
</ol> 
**Learning Curves:** <br>
 <img src="https://github.com/chirlgava/Credit_card/blob/main/figures/learning_curves.png" alt="Girl in a jacket"> 

**Model evaluation using test data:** <br>
![test image](https://github.com/chirlgava/Credit_card/blob/main/figures/model_evaluation.png)
