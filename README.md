# neural-network-challenge-1

# Neural Network Challenge: Predicting Student Loan Repayment

## 📚 Background

You work at a company that specializes in student loan refinancing. The company wants to improve how it predicts whether a borrower will repay their loan, allowing it to offer more accurate interest rates. Your task is to build a neural network model that predicts loan repayment success using a dataset provided by the business team.

## 🔍 Objective

Build, train, and evaluate a deep learning model using TensorFlow/Keras to predict student loan repayment based on borrower features. Then, use your model to make predictions and generate a classification report. Finally, provide a written discussion on designing a student loan recommendation system.

---

## 📁 Files Included

- `student_loans_with_deep_learning.ipynb` – Jupyter Notebook with all analysis steps.
- `student_loans.keras` – Saved trained model file.
- `README.md` – This file.

---

## ✅ Requirements & Deliverables

### Part 1: Prepare the Data
- ✅ Read the data from the provided CSV file into a DataFrame.
- ✅ Create the target (`y`) dataset from the `credit_ranking` column.
- ✅ Create the feature (`X`) dataset from the remaining columns.
- ✅ Split data into training and testing sets.
- ✅ Use `StandardScaler` to scale feature data.

### Part 2: Build & Evaluate the Model
- ✅ Construct a deep neural network using TensorFlow/Keras.
- ✅ Compile the model using `binary_crossentropy`, `adam` optimizer, and `accuracy` as a metric.
- ✅ Fit the model using 50–100 epochs.
- ✅ Evaluate the model's loss and accuracy on the test set.
- ✅ Save the trained model as `student_loans.keras`.

### Part 3: Make Predictions
- ✅ Reload the saved model.
- ✅ Use it to make predictions on the test dataset.
- ✅ Round raw probability predictions to binary values.
- ✅ Generate and display a classification report.

### Part 4: Recommendation System Discussion
- ✅ Describe the type of data needed for a student loan recommendation system.
- ✅ Explain the most suitable filtering method (collaborative, content-based, or context-based).
- ✅ Discuss two real-world challenges in building such a system.

---

## 🧠 Technologies Used

- Python
- Pandas
- NumPy
- TensorFlow / Keras
- Scikit-learn
- Google Colab

---

## 📝 Instructions to Run

1. Clone the repository:

