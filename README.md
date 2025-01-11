# workplace_absence

# Project Overview
The project focused on a dataset containing employee absenteeism records. Key tasks included:
- Cleaning and preprocessing the dataset.
- Engineering features for better model interpretability and prediction.
- Training and evaluating a logistic regression model to predict excessive absenteeism.
- Exporting the model and preprocessing pipeline for reuse.

# Project Objectives
The goal of this project is to understand the factors contributing to employee absenteeism, develop a robust predictive model for excessive absenteeism, and provide actionable insights and recommendations for workforce management.

# Technologies Used
- Python
- Pandas
- Numpy
- sklearn
- Pickle

# Methods Used
- Data Cleaning
- Data Preprocessing
- Machine Learning
  
# Key Findings
- Reason categories which are all health-related (especially Reason_3 and Reason_1), transportation expense, Children, and BMI strongly influence absenteeism.
- High performance on training data indicated a good fit.
- The model generalized well on unseen data.

# Recommendations
- Health Support Programs: Employers can invest in preventive healthcare measures, such as wellness programs or regular health check-ups, to reduce the frequency of disease-related absences (Reason_1).
- Maternity Benefits: Provide flexible leave policies and post-maternity support to manage absences due to pregnancy and childbirth (Reason_2).
- Safety Training: Accidents and poisonings (Reason_3) being the largest contributor suggest the need for workplace safety initiatives, ergonomic improvements, and employee training to mitigate risks.
- Telemedicine and Flexible Scheduling: For medical appointments (Reason_4), employers could consider options like telemedicine or scheduling flexibility to reduce the need for excessive absences.
- Provide support or incentives for employees with high transportation expenses or long commutes.
- Target interventions for older employees or those with children, as these factors influence absenteeism.

