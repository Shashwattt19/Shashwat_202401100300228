Classifying Plants Based on Water Needs
The goal of this project is to predict a plant's water requirement category (such as "Low", "Medium", or "High") using its environmental preferences and watering frequency.
Problem Overview
Plants have different water needs depending on factors like:

Sunlight exposure (e.g., low, medium, high)

Soil type (e.g., clay, loamy, sandy)

Watering frequency (e.g., daily, weekly)

Given a dataset of such features and corresponding water needs, we train a machine learning model to automatically classify new plants into one of the predefined watering categories.

🛠️ Solution Approach
Data Loading: Read the dataset (CSV file) into a Pandas DataFrame.

Preprocessing:

Handle missing values.

Encode categorical features using LabelEncoder.

Model Training:

Split the data into training and testing sets.

Train a machine learning model (Random Forest) on the training data.

Evaluation:

Predict on test data.

Evaluate accuracy and performance using metrics like classification_report
