# Airline Customer Satisfaction Analysis
This project aims to analyze airline customer satisfaction using various classification algorithms and ensemble methods. The dataset contains information about customer satisfaction levels, along with several features related to the customer's flight experience.

### Dataset
The dataset includes the following features:

1)satisfaction: Target variable indicating customer satisfaction (satisfied or dissatisfied)

2)Customer Type: Type of customer (Loyal Customer or Disloyal Customer)

3)Age: Age of the customer

4)Type of Travel: Type of travel (Personal Travel or Business Travel)

5)Class: Travel class (Eco, Business, or Eco Plus)

6)Flight Distance: Distance of the flight

7)Seat comfort, Departure/Arrival time convenient, Food and drink, Gate location, Inflight wifi service, Inflight entertainment, On-board service, Leg room service, Baggage handling, Checkin service, Cleanliness, Online boarding: Various service quality ratings (0 to 5)

8)Departure Delay in Minutes: Departure delay in minutes

9)Arrival Delay in Minutes: Arrival delay in minutes

### Analysis
In this project, I applied several machine learning algorithms to classify customer satisfaction, including:

Logistic Regression
Decision Trees
Random Forest
Gradient Boosting
XGBoost
Support Vector Machines (SVM)
k-Nearest Neighbors (k-NN)
Results
The performance of each model was evaluated using metrics such as accuracy, precision, recall, and F1-score. Ensemble methods like Random Forest and Gradient Boosting showed significant improvement in prediction accuracy compared to individual classifiers.

Repository Structure
data/: Contains the dataset (CSV file)
notebooks/: Jupyter notebooks with detailed analysis and model training
README.md: Project description and instructions

### Getting Started
Clone the repository:

bash
Copy code
git clone https://github.com/vijay0320/Airline-Customer_satisfaction-Classification.git
Install the required dependencies:

bash
Copy code
pip install -r requirements.txt
Run the Jupyter notebooks in the notebooks/ directory to reproduce the analysis.

### Findings
From the different models, we can conclude that ensemble methods such as Bagging and Boosting performed well in classifying.
Bagging with 20 estimators and XGB Classifier achieved an accuracy of 95%

### Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.
