# SALARY-PREDICTION-MODEL
The problem statement involves creating a Regression machine learning model to help TechWorks Consulting predict the salary of newly hired employees using data provided.
The data contains 8 feature columns such as College, city, role, previous CTC, previous job change, graduation marks, experience in months, and current CTC.

This MODEL should aligns with the company's goal of providing fair and competitive compensation to its employees based on various factors such as experience, qualifications, performance, and market trends.

By leveraging machine learning techniques, TechWorks Consulting aims to make data-driven decisions about salary rather than relying on subjective judgments or estimates. This approach can help ensure consistency and fairness in compensation across different employees, which they want to do.

The problem statement also highlights the importance of data pre-processing, including handling missing values, outliers, and transforming categorical variables into numerical representations. These steps are crucial for preparing the data and making it suitable for training a regression model.

Also the process of selecting a regression model involves analyzing the data, understanding feature importance, and evaluating the model's performance using metrics like Mean Squared Error (MSE), R-squared, and AIC.

#RANDOM FOREST With Best R2 Score: 0.6352305752115943 and Best Mean Squared Error: 62252182.47292912

I PREFERED RANDOM FOREST As 1st it has highest r2 Score. Other models also do have close r2 scores around 0.6 but Random forest has least MSE of 62252182.47292912. Where as model like Decision Tree HAS MSE of 66461034.01778529. Which is a very significant difference.

The list of r2 scores and MSE is giving below for other models

LINEAR REGRESSION Boosting - R-squared Score: 0.6106856351259594 Boosting - Mean Squared Error: 66441064.50404891

Decision Tree Decision Tree - R-squared Score: 0.6019663730145537 Decision Tree - Mean Squared Error: 67929108.8934694 Boosting - R-squared Score: 0.6105686228743474 Boosting - Mean Squared Error: 66461034.01778529 GRADIENT BOOSTIN R-squared Score: 0.6105058377521806 Mean Squared Error: 66471749.03559135 Ada Boost R-squared Score: 0.5982405252800125 Mean Squared Error: 68564968.52773441

XG BOOST R-squared Score: 0.6066004053222787 Mean Squared Error: 67138256.9053312 MODEL 8 RIDGE Ridge Regression - R-squared Score: 0.6105542649604114 Ridge Regression - Mean Squared Error: 66463484.364271395
