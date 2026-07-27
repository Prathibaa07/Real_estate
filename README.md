 #🏡 Real Estate House Price Prediction using Machine Learning

## 📌 Project Overview

This project demonstrates the application of Machine Learning techniques to predict house prices based on various property features. The project uses **Linear Regression** to estimate house prices and **K-Means Clustering** to group similar houses based on their characteristics.

The objective is to help users estimate house prices and understand patterns within the real estate dataset through visualization and clustering.

---

# 🎯 Project Objectives

* Load and preprocess a real estate dataset.
* Clean missing values from the dataset.
* Train a Machine Learning model using Linear Regression.
* Predict house prices for new properties.
* Evaluate model performance using standard regression metrics.
* Group houses into clusters using the K-Means algorithm.
* Visualize clusters and prediction results.

---

# 🛠 Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

---

# 📂 Dataset Description

The dataset contains information about residential properties.

### Features

* Area (Square Feet)
* Number of Rooms
* Build Year
* Location
* Street Type
* Furnishing Status
* Property Type
* Swimming Pool Availability
* House Price (Target Variable)

---

# 🔄 Project Workflow

### Step 1: Import Libraries

Import all required Python libraries.

### Step 2: Load Dataset

Load the dataset using Pandas.

### Step 3: Data Preprocessing

* Handle missing values
* Select required features
* Prepare data for training

### Step 4: Split Dataset

Split the dataset into:

* Training Data
* Testing Data

### Step 5: Train Machine Learning Model

Train a Linear Regression model using the training data.

### Step 6: Predict House Prices

Predict prices for:

* Test dataset
* New house details

### Step 7: Evaluate Model

Calculate:

* R² Score
* Prediction Results

### Step 8: K-Means Clustering

Group houses into clusters based on property characteristics.

### Step 9: Visualization

Generate graphs for:

* Actual vs Predicted Prices
* K-Means Cluster Visualization
* Prediction Error Distribution

---

# 📊 Outputs

The project generates the following outputs:

Mapping Cluster:

<img width="897" height="570" alt="Screenshot 2026-07-27 094300" src="https://github.com/user-attachments/assets/a7ccdcce-8ae7-4028-a1d3-b9566680e139" />

House Price Prediction:

<img width="564" height="452" alt="Screenshot 2026-07-26 150710" src="https://github.com/user-attachments/assets/6ba40a5a-7938-49d1-b394-414b2186a103" />

Prediction Error Distribution:

<img width="699" height="548" alt="Screenshot 2026-07-26 151740" src="https://github.com/user-attachments/assets/1cf89ce0-2d95-4b40-a2cb-833da23ad06f" />

K-Mean Clustering:

<img width="524" height="468" alt="Screenshot 2026-07-26 150935" src="https://github.com/user-attachments/assets/db393939-b5f1-47ca-8255-8206b4c8cc34" />




# 🤖 Machine Learning Algorithms Used

## 1. Linear Regression

Linear Regression predicts house prices based on numerical property features.

### Input Features

* Area
* Rooms
* Build Year

### Output

Predicted House Price

---

## 2. K-Means Clustering

K-Means groups similar houses into clusters without using price labels.

This helps identify similar types of properties based on their features.

---

# 📈 Model Evaluation

The project evaluates prediction performance using:

* R² Score
* Actual vs Predicted Comparison
* Error Distribution

---

# 📁 Project Structure

```
Real-Estate-House-Price-Prediction/

│── dataset_2.csv
│── Untitled2.ipynb
│── README.md

├── Output/
│   ├── actual_vs_predicted.png
│   ├── kmeans_clusters.png
│   ├── prediction_error.png
```

---

# ▶️ How to Run the Project

1. Download the project.
2. Open `Untitled2.ipynb` in Google Colab.
3. Upload the dataset (`dataset_2.csv`).
4. Run all notebook cells.
5. View the prediction results and graphs.

---


# 💡 Applications

* Real Estate Price Estimation
* Property Market Analysis
* Investment Planning
* Housing Price Prediction
* Smart Property Recommendation

---

# 🎓 Learning Outcomes

After completing this project, you will understand:

* Data preprocessing techniques
* Linear Regression for prediction
* K-Means Clustering
* Model evaluation
* Data visualization
* Real-world Machine Learning workflow
* House price prediction using Python

---

# 👩‍💻 Developed By

**Student Name:** Prathibaa P
**Course:** Bachelor of Computer Applications (BCA)
**Project Title:** Real Estate House Price Prediction using Machine Learning
**Tools Used:** Python, Google Colab, Scikit-learn, Pandas, Matplotlib
