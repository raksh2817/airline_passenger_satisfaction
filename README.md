# Airline Passenger Satisfaction Analysis

## Overview
This repository contains a comprehensive analytical and predictive modeling study on **Airline Passenger Satisfaction**. It leverages data science and machine learning techniques to uncover insights into factors influencing passenger satisfaction in the airline industry. The ultimate goal of the project is to empower airlines to strategically improve customer experiences, enhance passenger loyalty, and drive overall business growth.

![Airline Passenger Satisfaction Analysis](path_to_image_from_docx)

## Project Objective
The primary aim of this project is to deeply analyze and predict airline passenger satisfaction through various customer demographics, flight-related services, and operational metrics. Specifically, the project targets:

- **Identification** of key determinants driving passenger satisfaction.
- **Development** of robust predictive classification models capable of accurately identifying satisfied and dissatisfied passengers.
- **Provision** of actionable insights to help airlines enhance their customer service and operational efficiency.

## Dataset Description
- **Source**: Kaggle Airline Passenger Satisfaction dataset
- **Number of Records**: 129,880
- **Number of Features**: 23 (Categorical and Numerical)

### Key Variables
- **Demographic Factors**:
  - Gender
  - Age
  - Customer Type (Loyal vs Disloyal)
- **Travel Details**:
  - Type of Travel (Business, Personal)
  - Class (Business, Economy, Economy+)
  - Flight Distance
- **Service Quality Ratings**:
  - Inflight WiFi Service
  - Departure/Arrival Time Convenience
  - Ease of Online Booking
  - Food and Drink
  - Online Boarding
  - Seat Comfort
  - Cleanliness
- **Operational Metrics**:
  - Departure Delay in Minutes
  - Arrival Delay in Minutes

### Dataset Snapshot
![Dataset Snapshot](path_to_dataset_image_from_notebook)

## Exploratory Data Analysis (EDA)
Comprehensive exploratory analysis was performed to identify key trends and relationships within the data, including:
- **Univariate Analysis**: Distributions of demographics, service ratings, and travel specifics.
- **Bivariate Analysis**: Exploration of relationships between satisfaction and various factors like age, travel type, class, ease of booking, and service quality indicators.

### Sample EDA Visualizations
![EDA Visualizations](path_to_eda_image_from_notebook)

## Data Preparation and Feature Engineering
- Converted categorical features into numerical formats using encoding methods.
- Investigated and mitigated multicollinearity issues among predictive features.
- Performed data normalization and handled any missing values appropriately to maintain data quality.

## Predictive Modeling Approach
Various machine learning classification algorithms were systematically explored and evaluated:

### Baseline Model
- **Logistic Regression**: Established baseline performance metrics.

### Advanced Predictive Models
- **Decision Trees**: Chosen for ease of interpretation and flexibility.
- **Ensemble Methods**:
  - **Random Forest**: Improved predictive power by aggregating multiple decision trees.
  - **Light GBM**: Chosen for its high efficiency, accuracy, and scalability for large datasets.

## Model Evaluation and Optimization
- Model effectiveness evaluated using metrics including accuracy, precision, recall, and F1-score.
- Hyperparameter optimization conducted via Randomized Search Cross-Validation (CV) to fine-tune model performance and reliability.

### Model Evaluation Results
![Model Evaluation](path_to_model_evaluation_image_from_notebook)

## Key Findings and Insights
- Achieved outstanding predictive accuracy (**96.3%**) using ensemble methods, particularly Random Forest.
- Identified key influential factors affecting passenger satisfaction:
  - **Inflight Wi-Fi Service**: Passengers expressed significant dissatisfaction, highlighting critical improvement needs.
  - **Ease of Online Booking**: Crucial for customer satisfaction, especially among business travelers.
  - **Online Boarding Experience**: Positively correlated with higher overall passenger satisfaction.

## Conclusions and Recommendations
- Airlines should urgently enhance their inflight Wi-Fi services, optimize online booking systems, and streamline the online boarding experience.
- Utilizing these predictive models can significantly enhance strategic decisions, directing resources toward improvements most likely to yield higher passenger satisfaction and loyalty.

## Technologies Used
- **Python**
  - Libraries: Pandas, NumPy, Scikit-learn, Light GBM
- **Jupyter Notebook** for analysis and visualization

## References
- Kaggle Dataset
- Scholarly Articles:
  - "Customer Satisfaction in the airline industry: The role of service quality and price" (Asia Tourism Forum Conference, 2012)
  - "Customer Satisfaction in Airline Industry" (10.7763/IPEDR. 2014. V76. 12.)

## Contributor
- **Rakshith S.**

**Mentor**: Mr. Shashank

---
**Thank you for exploring this detailed analytical project on Airline Passenger Satisfaction!**

