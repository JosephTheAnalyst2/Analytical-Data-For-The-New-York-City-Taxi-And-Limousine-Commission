# NYC Taxi Tipper Prediction Analysis

This repository contains the analysis and machine learning modeling conducted for the New York City Taxi and Limousine Commission (NYC TLC) to predict whether a taxi cab rider will be a generous tipper. The project was completed by me, and this README outlines the objectives, methodologies, and future recommendations.

# Overview
The goal of this project was to design and implement a predictive model to identify generous tippers (defined as riders who tip 20% or more of the fare) to assist NYC TLC in providing better insights for taxi drivers. This approach was chosen to balance the interests of drivers and passengers, after rejecting an initial objective of predicting non-tippers due to ethical concerns.

### Project Highlights
Problem Statement: Build a model to predict whether a taxi rider will provide a tip ≥ 20%.
Solution: The team utilized machine learning models to predict generous tippers based on features such as trip itinerary, predicted fare amount, and time of day.
Outcome: A random forest model yielded the best results, with an F1 score of 0.7235, making it a strong candidate for beta testing.
Methodology

### Data Analysis:
Explored key variables influencing tipping behavior.
Assumed features like trip details and fare amount would correlate with tipping behavior.

### Modeling:
Implemented and tested two machine learning models: Random Forest and XGBoost.
Random Forest slightly outperformed XGBoost in precision, recall, and F1 score.
Evaluation Metrics:
F1 Score: 0.7235
The model demonstrated reasonable precision, recall, and overall accuracy.
Results Summary
The resulting model is effective in predicting generous tippers with reasonable accuracy. The random forest model is recommended for beta testing with taxi drivers to evaluate real-world applicability.

Next Steps
To improve the model's accuracy and extend its application:

### Data Collection:
Include more granular data, such as past tipping behavior and user/driver-level features.
Advanced Techniques:
Apply K-means clustering to identify patterns in tipping behavior and segment customers for better insights.
Beta Testing:
Deploy the model in a pilot program with taxi drivers to gather feedback and refine predictions.

# How to Use This Repository
### Clone the repository:

`git clone https://github.com/yourusername/nyc-tipper-prediction.git
cd nyc-tipper-prediction`

### Explore the project files:
data/: Contains preprocessed datasets.
models/: Includes trained Random Forest and XGBoost models.
notebooks/: Jupyter notebooks detailing data analysis and model implementation.
reports/: Summary of results and visualizations.

Run the analysis:
Open the notebooks to reproduce the results.
Scripts can be executed for end-to-end data processing and modeling.

# Future Work
Automatidata is open to consulting with NYC TLC to enhance the model with additional data and refine the prediction process for better results.

