Title : Predicting Diabetes Likelihood Using Machine Learning

Description :
This project explores the use of machine learning algorithms to predict the likelihood of diabetes in patients based on a set of features. The dataset consists of information on patients, including their gender,
age, history of hypertension, heart disease, smoking, BMI, HbAlc level, and blood glucose level. The target variable is whether the patient has diabetes or not.

Highlights :
Finding The Top 10 Combinations With The Highest Probabilities Of Getting Diabetes : 

![jn1](https://github.com/rbhavitha/Predicting-Diabetes-Likelihood-Using-Machine-Learning-/assets/71348485/7c2f7f44-68e0-4d0d-8380-63a652647089)

Here we used a logistic regression classifier to predict the probabilities of getting diabetes for various combinations of demographic and behavioral features.
*Firstly we defined age groups, sexes, and smoking habits as arrays.
*Created a list of all possible combinations of age, sex, and smoking habit.
*Calculated the mean feature values of the training set.
*Added the mean feature values to the list of combinations.
*Used the logistic classifier to predict the probability of getting diabetes for each combination.
*Sorted the list of combinations and probabilities in descending order.

Then lastly we printed the top 10 combinations with the highest probabilities of getting diabetes, along with their corresponding demographic and behavioral features.

![jn2](https://github.com/rbhavitha/Predicting-Diabetes-Likelihood-Using-Machine-Learning-/assets/71348485/6daa8e6e-0211-4c6c-8494-d8d0f83aa3ae)

*From the above, it appears that individuals who are male, smokers, and 80 years of age have a higher likelihood of developing diabetes.
*Individuals who are make , non-smoker and 60 years of age have less chance of developing diabetes.

Accuracy Comparison Of Models :
![jn3](https://github.com/rbhavitha/Predicting-Diabetes-Likelihood-Using-Machine-Learning-/assets/71348485/4d09d7c9-f793-422d-b6c1-79de7489807f)

Random Forest and Decision Tree are the best models on this data set.
