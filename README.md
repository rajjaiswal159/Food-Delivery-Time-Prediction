# 🚚 Food Delivery Time Prediction
This project focuses on predicting the estimated time of arrival (ETA) for food deliveries using machine learning regression models. The goal is to build a reliable model that can predict delivery time based on various features like distance, weather, traffic, and delivery person characteristics.

# 📌 Problem Statement
Given a dataset containing various features of food deliveries (e.g., distance, weather, delivery person ratings), the task is to predict the time taken for food delivery. This can help food delivery platforms optimize routing, customer expectations, and resource allocation.

# 📊 Dataset Overview
The dataset includes the following features:

Delivery_person_Age

Delivery_person_Ratings

Distance(km)

Type_of_order

Type_of_vehicle

Weather

Road_traffic_density

multiple_deliveries

Time_taken(min) (Target)

# 🧹 Data Preprocessing
Handled missing values.

Applied encoding to categorical features.

Scaled numerical features using StandardScaler.

Combined transformations using ColumnTransformer.

# 🧠 Models Used
Several machine learning models were evaluated:

Linear Regression

K-Nearest Neighbors (KNN)

Support Vector Regressor (SVR)

Decision Tree Regressor

Random Forest Regressor

Optuna for hyperparameter tuning

# 📈 Evaluation Metrics
Mean Absolute Error (MAE)

R² Score

Cross-Validation Score

# ✅ Results
The best-performing model yielded:

MAE ≈ 5 minutes

R² Score ≈ 42%

MAPE ≈ 24%

# 📁 Project Structure

food-delivery-time.ipynb      # Jupyter notebook with full code
Food_Delivery_Times.csv       # Dataset used for modeling (not uploaded here)
requirements.txt              # List of dependencies to run the notebook

⚙️ Installation
Install the required libraries using:

```
pip install -r requirements.txt
requirements.txt

matplotlib>=3.4.0
numpy>=1.22.0
optuna>=3.0.0
pandas>=1.3.0
seaborn>=0.11.0
scikit-learn>=1.0
```
# 📌 How to Run
Clone the repo.

Install the required packages (see above).

Open and run food-delivery-time.ipynb.

📬 Contact
Made with ❤️ by Raj Jaiswal
Feel free to connect on LinkedIn or view my other projects on GitHub
