# neural-network-challenge-1
Module 18 Challenge
# Neural Network Challenge: Student Loan Repayment Prediction

## Background
In the financial sector, predicting the likelihood of loan repayment is crucial for setting interest rates that accurately reflect risk. This project focuses on the development of a model to predict the repayment of student loans using machine learning and neural network techniques. With a dataset of past student loan recipients, including features such as credit ranking, the goal is to create a neural network model that can assess the probability of loan repayment.

## Repository Setup
1. **Create** a new GitHub repository named `neural-network-challenge-1`.
2. **Clone** the repository to your local machine.
3. **Add** the starter file `student_loans_with_deep_learning.ipynb` to your local repository.
4. **Push** the changes to GitHub.
5. **Upload** the notebook to Google Colab for development and periodically push updates to GitHub to track changes.

## Files
- **Starter Notebook:** `student_loans_with_deep_learning.ipynb` contains the template code for the project.
- **Data:** Download the student loan dataset from [here](https://static.bc-edx.com/ai/ail-v-1-0/m18/lms/datasets/student-loans.csv).

## Instructions

### Part 1: Data Preparation
1. **Load Data:** Import the student loans dataset into a Pandas DataFrame. Analyze the DataFrame to identify potential features and the target variable.
2. **Preprocess Data:** Define `credit_ranking` as the target variable (`y`) and the remaining columns as features (`X`).
3. **Split Data:** Divide the dataset into training and testing sets.
4. **Scale Features:** Utilize scikit-learn's `StandardScaler` to normalize the features data.

### Part 2: Model Compilation and Evaluation
1. **Design Neural Network:** Create a deep neural network using TensorFlow's Keras. Begin with a two-layer model utilizing the relu activation function.
2. **Compile and Fit Model:** Use the `binary_crossentropy` loss function, `adam` optimizer, and track accuracy. Start with a moderate number of epochs (50-100).
3. **Evaluate Model:** Assess the model's performance on the test dataset to determine loss and accuracy.
4. **Save Model:** Export the trained model as `student_loans.keras`. Ensure to download the model from Colab for GitHub uploading.

### Part 3: Prediction
1. **Reload Model:** Import the previously saved model.
2. **Make Predictions:** Apply the model to the testing dataset, converting predictions to binary values.
3. **Classification Report:** Generate and analyze a classification report comparing predictions and actual data.

### Part 4: Recommendation System Discussion
1. **Data Requirements:** Describe the essential data for a student loan recommendation system, explaining its relevance.
2. **Filtering Method:** Determine whether collaborative filtering, content-based filtering, or context-based filtering is more appropriate based on the chosen data. Justify your selection.
3. **Challenges:** Identify two significant challenges in creating a student loan recommendation system, discussing their implications.

## Submission
- Ensure all work is pushed to the GitHub repository `neural-network-challenge-1`.
- Include a link to the Colab notebook in the README for easy access and evaluation.

## Note
This project requires a practical application of data science and neural network concepts in a real-world scenario. It's designed to enhance your understanding of machine learning workflows, from data preprocessing to model evaluation and application.
