Title : Predicting Diabetes Likelihood Using Machine Learning

Description :
This project explores the use of machine learning algorithms to predict the likelihood of diabetes in patients based on a set of features. The dataset consists of information on patients, including their gender,
age, history of hypertension, heart disease, smoking, BMI, HbAlc level, and blood glucose level. The target variable is whether the patient has diabetes or not.

Highlights :
Finding The Top 10 Combinations With The Highest Probabilities Of Getting Diabetes : 

![jn1](https://github.com/rbhavitha/Predicting-Diabetes-Likelihood-Using-Machine-Learning-/assets/71348485/9197ddd1-24d6-446d-b4b4-dddeee5af879)

Here we used a logistic regression classifier to predict the probabilities of getting diabetes for various combinations of demographic and behavioral features.
*Firstly we defined age groups, sexes, and smoking habits as arrays.
*Created a list of all possible combinations of age, sex, and smoking habit.
*Calculated the mean feature values of the training set.
*Added the mean feature values to the list of combinations.
*Used the logistic classifier to predict the probability of getting diabetes for each combination.
*Sorted the list of combinations and probabilities in descending order.

Then lastly we printed the top 10 combinations with the highest probabilities of getting diabetes, along with their corresponding demographic and behavioral features.
![jn2](https://github.com/rbhavitha/Predicting-Diabetes-Likelihood-Using-Machine-Learning-/assets/71348485/1499d6be-f8e7-44b7-bdcc-5b06cd89b8a4)

*From the above, it appears that individuals who are male, smokers, and 80 years of age have a higher likelihood of developing diabetes.
*Individuals who are make , non-smoker and 60 years of age have less chance of developing diabetes.

Accuracy Comparison Of Models :
![jn3](https://github.com/rbhavitha/Predicting-Diabetes-Likelihood-Using-Machine-Learning-/assets/71348485/3a77f2aa-35c0-43d8-9b83-4db1a5f4ddd.
Random Forest and Decision Tree are the best models on this data set.
