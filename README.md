# Age and Generation Prediction Project

## Project Overview

This project aims to tackle the challenges of working with an extremely imbalanced dataset by applying both regression and classification methods. Imbalanced datasets are a common challenge in data science, often compromising model accuracy and reliability. To mitigate these issues, we implemented a range of strategies and models to achieve strong performance across both classification and regression tasks. The focus of this project is on predicting the age and generational group (Millennial, Gen X, Boomer) of users based on their profiles from the OKCupid dating platform. By employing supervised machine learning techniques, the project aspires to build model capable of accurately determining these demographic details from the provided profile data.

## Methodology

1. **Data Preprocessing**
   - Removed rows with missing values.
   - Combined multiple essay columns into a single text feature.
   - Encoded categorical variables using Label Encoding.
   - Transformed specific features like `body_type`, `diet`, `education`, and `drinks` into more general categories.

2. **Exploratory Data Analysis (EDA)**
   - Explored distributions of various features like age, body type, and education.
   - Visualized correlations between features.
   - Identified potential outliers and handled missing data.

3. **Feature Engineering**
   - Created new features such as text length from essays.
   - Generated dummy variables for categorical features.

4. **Model Training**
   - Split the data into training and test sets.
   - Trained different machine learning models (e.g., Linear Regression, Logistic Regression) to predict age and generation.
   - Used metrics like R² score, Mean Squared Error (MSE), and classification accuracy to evaluate model performance.

5. **Model Evaluation**
   - Evaluated the trained models on test data.
   - Analyzed confusion matrices and classification reports for generation prediction.
   - Performed error analysis to improve model accuracy.

## Results

The final models demonstrated satisfactory performance in predicting user age and generation.
