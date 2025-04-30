# Introduction to Smoking and Drinking
Smoking and alcohol consumption has over the years been a global challenging phenomenon with an overriding effect on consumer’s immediate behaviour and general long-term health. Studies over the years have found existing relationships between smoking and alcohol consumption, and its effect on the human body, which include, cancers, birth defects, cardiovascular diseases and other medical conditions.
Global projection studies indicate that smoking has over the years had an adverse effect on the health and well-being of smokers. It also shows that tobacco smoking is a major cause of premature death and disabilities in the world.



#Distribution of population who are drinkers

![image](https://github.com/user-attachments/assets/7e649be2-ccae-44f3-b944-8110d359233c)

#Distribution of population who are smokers

![image](https://github.com/user-attachments/assets/338c5ffb-e253-4ee5-be5d-9b8abb809125)

![image](https://github.com/user-attachments/assets/80b60080-51b4-48f9-aeee-45609dbff4bc)

![image](https://github.com/user-attachments/assets/eb713f2f-0212-4e1f-9b2d-38c7ce37aede)

The performance results of the Logistic Regression Model show an accuracy score of 0.68 which shows that the model correctly predicted 68% of the test dataset. The classification report shows a precision of 0.83 in class 1, this means that 83% of the data points belong to the actual class 1. The recall score of 0.79 shows that of all data points in class 1, 79% of data points were correctly identified by the model. The F1 Score of 0.81 recorded for class 1 is the weighted harmonic mean of precision and recall for class 1 at 81%. The precision score for class 2 is 0.4 showing that 43% of data points belong to class 2. The recall score of class 2 is 0.35 showing that of all in class 2, 35% of data points were correctly identified by the model. The F1 score of class 2 is 0.39 showing the weighted harmonic mean of precision and recall for class 2 at 39%.
The precision score for class 3 is 0.48 which means that 48% of data points belong to class 3. The recall score for class 3 is 0.63 which shows that 63% of data points were correctly identified by the model. The F1 score of 0.55 in class 3 shows the weighted harmonic mean of precision and recall for class 3 at 55%.

![image](https://github.com/user-attachments/assets/8184d086-318c-4120-b788-584c28006137)

Figure 15: LIME Model with the Smoking Feature

The figure above shows the LIME (Local Interpretable Machine-agnostic Explanation) model for smoking. After training the model using LIME, it explained the effect of each feature on the target variable(smoking). It displayed the probabilities of both classes, denoting that the probability of persons in the population predicted as non-smokers lies at 87% and the probability of persons in the population predicted as quit smokers lies at 6% while the probability of active smokers is 7%. Also, active smokers have their BMI, cholesterol levels and livers (SGOT_ALT and SGOT_AST features) highly affected. 


# Conclusion 
The Analysis of smoking and drinking has revealed new insights which could be beneficial to the promoting the health status of a population, reduce risks associated with these practices and provide information that helps to promote healthy practices which will mitigate smoking and drinking. The results can be used to determine the body signals that are negatively affected by smoking and drinking behaviours. The models built can be used to predict the smoking and drinking status of persons, for early detection of symptoms in persons who are exposed to secondary smoke for timely intervention.










