# Loan Eligibility Prediction Model

## Overview
This repository contains a machine learning model for predicting loan eligibility. The model utilizes various features such as gender, marital status, dependents, education, applicant income, coapplicant income, loan amount, loan amount term, credit history, property area, and loan status to determine whether an individual is eligible for a loan or not. The model was trained using a support vector machine (SVM) classifier and achieved a test accuracy score of 81.2%.

## Dataset
The dataset used for training and testing the model contains loan information, with each row representing a single loan application. The features include:
- Loan_ID: Unique identifier for each loan application
- Gender: Gender of the applicant (male/female)
- Marital_Status: Marital status of the applicant (married/single)
- Dependents: Number of dependents
- Education: Education level of the applicant (graduate/not graduate)
- Self_Employed: Employment status of the applicant (self-employed/not self-employed)
- Applicant_Income: Income of the applicant
- Coapplicant_Income: Income of the coapplicant
- Loan_Amount: Amount of the loan applied for
- Loan_Amount_Term: Term of the loan (in months)
- Credit_History: Credit history of the applicant (1 for good credit history, 0 for bad credit history)
- Property_Area: Area where the property is located (urban/rural/semiurban)
- Loan_Status: Status of the loan application (eligible/not eligible)

## Steps Taken
1. **Dependencies**: Imported necessary libraries for data preprocessing, model training, and evaluation.
2. **Data Cleaning**: Replaced text data with numerical data using the replace function to prepare the dataset for model training.
3. **Data Splitting**: Separated the dataset into features (X) and labels (Y) for training and testing the model.
4. **Model Training**: Utilized a support vector machine (SVM) classifier to train the loan eligibility prediction model.
5. **Model Evaluation**: Achieved a test accuracy score of 81.2%, indicating the model's performance in predicting loan eligibility.

## Files Included
- `loan_eligibility_prediction.ipynb`: Jupyter Notebook containing the code for data preprocessing, model training, and evaluation.
- `loan_eligibility_prediction.py`: Python script equivalent of the Jupyter Notebook for easy execution.
- `loan_eligibility_prediction.pkl`: Serialized model file saved using joblib for future use.
- `train_u6lujux_CVtuZ9i(1).csv`: Sample dataset containing loan application information.

## Usage
To use the model for loan eligibility prediction:
1. Clone the repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the `loan_eligibility_prediction.py` script or open the `loan_eligibility_prediction.ipynb` notebook in a Jupyter environment.
4. Provide loan application data to the model for prediction.
5. The model will output predictions indicating whether the loan application is eligible or not.

## Conclusion
This machine learning model provides a reliable solution for predicting loan eligibility based on various applicant and loan-related features. Further enhancements and optimizations can be made to improve the model's performance and robustness.

For any questions or feedback, feel free to contact the repository owner.
