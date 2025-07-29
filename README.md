---

## Data Sources

The dataset includes:

- **Order & Time Data:**
  `Order_Date`, `Time_Orderd`, `Time_Order_picked`
- **Delivery Partner Data:**
  `Delivery_person_Ratings`, `Delivery_person_Age`, `Vehicle_condition`
- **Order Details:**
  `Type_of_order`, `Type_of_vehicle`, `multiple_deliveries`
- **Environment Factors:**
  `Weather_conditions`, `Road_traffic_density`, `Festival`
- **Location Data:**
  `Restaurant_latitude`, `Restaurant_longitude`,
  `Delivery_location_latitude`, `Delivery_location_longitude`
- **Target Variable:**
  `Time_taken(min)` – the delivery time to predict.

---

## Key Steps & Features

1. **Data Loading & Preprocessing**
   - Handle missing values
   - Convert columns to correct data types
   - Extract useful features (e.g., day of week, order hour, distance)

2. **Exploratory Data Analysis (EDA)**
   - **Visualizations**:
     - Order type popularity
     - Delivery ratings vs delivery time
     - Multiple deliveries impact
     - Day-of-week trends
     - Orders by time of day
     - Vehicle condition impact
     - Festival vs Non-festival comparisons
     - Distance vs Delivery time
     - Correlation heatmap

3. **Feature Engineering**
   - Calculate distance using geolocation
   - Encode categorical features

4. **Modeling**
   - Train/test split
   - Random Forest Regressor (and other models)
   - Evaluate using MAE, RMSE, R²

---

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `geopy`

### Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/Sahil-Verma_131102/Food_Delivery_Time.git
   cd Food_Delivery_Time
