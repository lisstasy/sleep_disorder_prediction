# Sleep Disorder Prediction Project

## Overview

This project involves the analysis and classification of sleep and cardiovascular metrics, along with lifestyle factors, for close to 400 fictive persons. The dataset is designed to address the requirements of a health insurance company, aiming to identify whether a potential client is likely to have a sleep disorder. The company intends to use this information to determine the premium for the client.

## Objective

The primary objective of this project is to automatically identify potential sleep disorders using machine learning classification techniques.

## Problem Solution

To achieve the project's goal, a classifier will be constructed to predict the presence of a sleep disorder based on various columns in the dataset.

## Dataset Source

The dataset was sourced from [Kaggle] https://www.kaggle.com/datasets/uom190346a/sleep-health-and-lifestyle-dataset/

## Project Structure

- `data.csv`: The main dataset file.
- `prediction.ipynb`: Jupyter Notebook containing the data analysis code.

## Dataset Information

The dataset contains the following columns:

- Person ID
- Gender
- Age
- Occupation
- Sleep Duration: Average number of hours of sleep per day
- Quality of Sleep: Subjective rating on a 1-10 scale
- Physical Activity Level: Average number of minutes of daily physical activity
- Stress Level: Subjective rating on a 1-10 scale
- BMI Category
- Blood Pressure: Indicated as systolic pressure over diastolic pressure
- Heart Rate: In beats per minute
- Daily Steps
- Sleep Disorder: One of None, Insomnia, or Sleep Apnea

## Project Workflow

1. **Data Understanding:**
   - Load the data and check the first few rows.
   - Examine data types and identify missing values.

2. **Exploratory Data Analysis (EDA):**
   - Visualize relationships between variables.
   - Identify patterns and correlations.
  
3. **Data Preprocessing:**
   - Encode categorical variables.
   - Explore and transform features as needed.

4. **Model Development:**
   - Split the data into training and testing sets.
   - Experiment with different classification algorithms (Logistic regression, Ridge, SVM, Random Forest Classifier) with cross-validation
  
5. **Model Evaluation:**
   - Evaluate the models' performances (Cross-Validation F1_weighted and classification report).
   - Fine-tuning.

6. **Executive summary and Recommendations:**
   

## Instructions

1. Clone the repository.
2. Explore the dataset and follow the analysis in the provided Jupyter Notebook.
3. Run the notebook to understand the project workflow.
4. Contribute to model improvement if interested.

Feel free to explore, learn, and contribute to the sleep disorder classification project!

