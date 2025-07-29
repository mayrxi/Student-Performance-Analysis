
# End-to-End Machine Learning Project: Student Performance Prediction

## Overview
This project demonstrates a complete end-to-end machine learning pipeline to predict student performance based on various factors. It involves all stages of a machine learning project, including data acquisition, preprocessing, analysis, model training, and deployment. The solution is deployed on the Flask framework, providing an interactive web application for predictions.

---

## Key Features

### 1. Data Acquisition
- **Dataset Used:** A dataset related to student performance, containing features such as demographics, academic records, and other relevant details.
- **Source:** Publicly available educational datasets.
- **Goal:** To predict students' scores based on input features.

---

### 2. Data Preprocessing
- **Steps Involved:**
  - **Handling Missing Values:** Used appropriate imputation techniques to fill missing values.
  - **Categorical Encoding:** Converted categorical features into numerical values using one-hot encoding and label encoding.
  - **Scaling:** Applied feature scaling using methods like StandardScaler to standardize data for better model performance.

---

### 3. Exploratory Data Analysis (EDA)
- **Objective:** To understand the data distribution and relationships between features.
- **Visualizations:**
  - Correlation heatmaps to identify feature importance.
  - Histograms and box plots to check data distributions and outliers.
  - Scatter plots for visualizing relationships between features and target variables.

---

### 4. Feature Engineering
- **Purpose:** To enhance model performance by creating new features or modifying existing ones.
- **Steps:**
  - Removed redundant or less important features based on correlation analysis.
  - Engineered new features by combining existing ones to capture additional insights.

---

### 5. Model Selection and Training
- **Algorithms Tested:**
  - Linear Regression
  - Decision Trees
  - Random Forest
  - Gradient Boosting (CatBoost)
- **Best Model:** Identified the best-performing model based on accuracy, mean squared error (MSE), and other evaluation metrics.
- **Hyperparameter Tuning:** Applied Grid Search and Random Search to optimize model performance.

---

### 6. Model Evaluation
- **Metrics Used:**
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - R-squared (R²) score
- **Insights:** The model was validated using cross-validation to ensure generalizability.

---

### 7. Deployment
- **Platform Used:** Flask
- **Features:**
  - User-friendly web interface for inputting student data.
  - Real-time predictions of student scores based on the trained model.
  - Visualization of feature importance and other insights.

---

## Installation and Usage

### Prerequisites
- Python 3.6+
- Required libraries: pandas, scikit-learn, matplotlib, seaborn, Flask

### Installation
1. Clone the Repository:
   ```bash
   git clone https://github.com/your-repository-link.git
   ```
2. Navigate to the Project Directory:
   ```bash
   cd student-performance-prediction
   ```
3. Install Dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Running the Application
1. Run the Flask app:
   ```bash
   python app.py
   ```
2. Open a browser and go to `http://localhost:5000/` to interact with the application.

---

## Results
- The deployed model achieves high accuracy in predicting student scores.
- Provides valuable insights into feature importance and relationships affecting performance.

---

## Future Work
- Expand the dataset to include more diverse features.
- Enhance the deployment with cloud hosting for wider accessibility.
- Incorporate additional machine learning models for comparison.

---

## Acknowledgements
- **Flask:** For creating a robust web application framework.
- **scikit-learn:** For machine learning model training and evaluation.
- **Dataset Contributors:** For providing the student performance dataset.

---

## Author
This project was developed as part of an initiative to explore end-to-end machine learning workflows and their deployment.
