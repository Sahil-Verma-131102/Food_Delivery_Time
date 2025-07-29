Food Delivery Time Analysis & Prediction
This project analyzes a food delivery dataset to perform Exploratory Data Analysis (EDA) and build a machine learning model to predict delivery time. It explores factors affecting delivery performance such as delivery person ratings, traffic, weather, distance, and order characteristics.

Project Objectives
Data Cleaning & Preprocessing

Handle null values

Convert data types

Extract useful features (date, time, distance)

Exploratory Data Analysis (EDA)

Understand trends and patterns through visualizations

Key insights:

Impact of delivery ratings on time

Traffic, weather, and festival impact

Order trends by day and hour

Correlations between numeric features

Predictive Modeling

Machine learning models used:

Random Forest Regressor

XGBoost (optional)

Evaluation metrics:

R² Score

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

Key Visualizations
Order Type Popularity (Pie Chart)

Ratings vs Delivery Time (Scatter)

Multiple Deliveries vs Time (Boxplot)

Day of Week vs Avg Time (Bar/Line)

Orders by Time of Day (Histogram)

Vehicle Condition Impact (Boxplot)

Festival vs Non-Festival (Bar Chart)

Distance vs Time (Scatter + Regression)

Correlation Heatmap

Dataset
The dataset contains the following key columns:

Order_Date, Time_Orderd, Time_Order_picked

Delivery_person_Ratings, Delivery_person_Age, Vehicle_condition

Type_of_order, Type_of_vehicle, multiple_deliveries

Weather_conditions, Road_traffic_density, Festival

Restaurant_latitude/longitude, Delivery_location_latitude/longitude

Target: Time_taken(min)

Tech Stack
Python Libraries:
pandas, numpy, matplotlib, seaborn,
scikit-learn, geopy (for distance calculation)
How to Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/Sahil-Verma-131102/Food_Delivery_Time.git
cd Food_Delivery_Time
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Open the Jupyter Notebook:

bash
Copy
Edit
jupyter notebook Food_Delivery_Time.ipynb
Follow the steps inside the notebook to run EDA and modeling.

Results
Key insights about delivery time factors are derived.

A Random Forest model was trained to predict Time_taken(min) with good accuracy.

Business recommendations are provided based on findings.

Future Work
Hyperparameter tuning for better prediction.

Include real-time weather/traffic data.

Build a dashboard for live delivery time predictions.

Author
Sahil Verma

