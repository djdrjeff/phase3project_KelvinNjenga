# phase3project_KelvinNjenga
## Project Overview:

This project focuses on analyzing traffic crash data from the City of Chicago to predict the primary factors contributing to accidents. The objective is to support organizations like Vehicle Safety Boards and city administrations in identifying trends and implementing strategies to reduce traffic accidents.

## Dataset
Source: The dataset is obtained from the City of Chicago's Traffic Crashes dataset.

## NB: To access the Dataset steps below need to be followed

1. On the git repository there is a notepad docuement which has alink to the dataset used for this project.
2. Click on the link it will take you to a goodle drive folder whjere teh data is residing
3. The above was done since the data was too big to fit in the git repository.

## Modeling Process

# Baseline Model: 
Logistic Regression was used as the initial baseline model.
# Feature Selection: 
Features were chosen based on their correlation with the target variable and domain expertise.
# Model Comparison: 
Various models, including Logistic Regression, Ridge Classifier, Random Forest, and Gradient Boosting, were trained and evaluated.
# Hyperparameter Tuning: 
Hyperparameters were optimized using RandomizedSearchCV to enhance model performance.
# Final Model: 
Gradient Boosting emerged as the top-performing model, selected based on its accuracy and other evaluation metrics.


## Results
Best Model: Gradient Boosting

Accuracy: 1.00%

Key Features: The most important features contributing to the model's predictions were Weather_Condition_Mode, Speed_Weather_Interaction, and Is_Weekend.


## Insights and Recommendations

# Traffic Management:
 The analysis indicates that weather conditions and speed limits play a critical role in contributing to crashes. Enforcing stricter speed regulations during adverse weather conditions could help reduce accident rates.

# Policy Changes:
 Prioritize enhancing road infrastructure and improving traffic control systems in areas identified with high accident frequencies.

# Further Analysis:
 Conduct additional studies on the influence of time of day and specific locations (latitude and longitude) on crash rates to enable more targeted and effective interventions.


 