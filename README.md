# Introduction to Smoking and Drinking
The research project titled "Analysis of Smoking and Drinking Behaviour for Predictive Intervention" aimed to explore the use of machine learning models in identifying and mitigating the health risks associated with smoking and alcohol consumption. The objective was to leverage data-driven approaches to uncover patterns in health data, predict harmful behaviours, and provide timely interventions for affected individuals and public health stakeholders.

# Objectives of Analysis
•	To predict the smoking and Drinking status of persons in a population.
•	To predict the health status of secondary smokers or persons who are not primarily smokers but are exposed to a smoke environment.
•	To determine the relationship between the body signals and the smoking or drinking status of a person.
•	To determine the machine learning models that are effective in prediction of smoking and drinking.
•	To identify the stakeholders and gaps in this research and how they are being addressed.

# Methods and Tools used for Data Analysis
1.	Several machine learning algorithms were employed including Random Forest, Logistic Regression, and Support Vector Machine (SVM) to analyse the dataset. In addition, LIME (Local Interpretable Model-agnostic Explanations) was applied to interpret the black-box models and explain the significance of individual features contributing to smoking and drinking predictions.
2.	Data pre-processing and cleaning using Python libraries (Pandas, NumPy).
3.	Exploratory Data Analysis (EDA) using Matplotlib and Seaborn to identify distributions, correlations, and outliers.
4.	Model development using Scikit-learn, followed by evaluation with metrics such as precision, recall, F1-score, and accuracy.
5.	Explainability techniques (LIME) to determine which physiological indicators were most influenced by smoking and drinking.

#Distribution of population who are drinkers

![image](https://github.com/user-attachments/assets/7e649be2-ccae-44f3-b944-8110d359233c)

#Distribution of population who are smokers

![image](https://github.com/user-attachments/assets/338c5ffb-e253-4ee5-be5d-9b8abb809125)

![image](https://github.com/user-attachments/assets/80b60080-51b4-48f9-aeee-45609dbff4bc)

![image](https://github.com/user-attachments/assets/eb713f2f-0212-4e1f-9b2d-38c7ce37aede)

![image](https://github.com/user-attachments/assets/8184d086-318c-4120-b788-584c28006137)

Figure 15: LIME Model with the Smoking Feature

# Key Findings
Our Random Forest model outperformed prior studies in precision (83%), though its accuracy (69%) was lower than previous benchmarks (84.4%). Nevertheless, it demonstrated robust consistency across other evaluation metrics (recall and F1-score = 83%). LIME analysis revealed key physiological signals impacted by smoking, such as BMI, cholesterol levels, and liver function (SGOT_ALT and SGOT_AST).
Drinking was found to affect a broader range of indicators, including kidney function, haemoglobin levels, waistline, blood sugar, blood pressure, and eyesight.

# Project Objectives Achieved
•	Predicted smoking and drinking status accurately using machine learning techniques.
•	Identified health risks for secondary smokers (individuals exposed to second-hand smoke).
•	Determined correlations between body signals and harmful health behaviours.
•	Compared performance across various ML models and introduced explainability via LIME.
•	Mapped relevant public health stakeholders and discussed existing research gaps.
•	Impact and Practical Implications
•	Enhanced Workforce Productivity: Early identification of health risks aids in reducing illness-related absenteeism and promoting economic vitality.
•	Healthcare Cost Reduction: Predictive interventions minimize treatment costs for smoking and alcohol-related diseases, supporting families and national health systems.
•	Mental Health Support: By understanding the physical toll of these behaviours, governments can develop targeted support and addiction recovery programs.
•	Policy Formation: Findings can shape public health policies around prevention, screening, and education regarding substance abuse and wellness.


# Conclusion and Recommendations
This study highlights the transformative potential of artificial intelligence in healthcare, demonstrating how predictive models and data-driven insights can effectively identify and address harmful behavioral patterns. Based on our findings, we recommend sustained investment in AI-enabled public health monitoring systems, the integration of physiological metrics to support early diagnosis and targeted interventions, and the adoption of model explanability techniques such as LIME to enhance transparency and trust in machine learning applications. This project exemplifies my dedication to impactful research, my capability to lead data-driven initiatives, and my preparedness for doctoral study, particularly at the intersection of AI, public health, and social impact.
 








