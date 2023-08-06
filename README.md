# LoanFit

## Project Overview
LoanFit is a predictive modeling project aimed at determining the eligibility of loan applicants based on their historical data. Utilizing machine learning techniques, LoanFit analyzes various applicant features to predict the likelihood of loan approval. The project leverages Python's data manipulation and machine learning libraries to build an efficient and accurate predictive model.

## Project Structure
The project repository is structured as follows:

- `EDA.py`: Contains the Exploratory Data Analysis (EDA) script.
- `LoansTrainingSetV2.csv`: Training dataset containing historical loan application data.
- `test_data.csv`: Test dataset for model evaluation.
- `dataset.py`: Script for data loading, preprocessing, and feature engineering.
- `README.md`: Project documentation.

## Key Features
1. **Exploratory Data Analysis (EDA)**
   - Analysis and visualization of key features and distributions.
   - Identification and handling of missing values and outliers.
   - Transformation of categorical variables.

2. **Data Preprocessing**
   - Loading and cleaning of datasets.
   - Feature engineering and selection.
   - Preparation of data for model training.

3. **Predictive Modeling**
   - Implementation of various machine learning algorithms (Logistic Regression, Decision Trees, Random Forests).
   - Hyperparameter tuning and cross-validation to optimize model performance.
   - Evaluation of model accuracy using metrics such as precision, recall, and F1-score.

## Installation
To set up the project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/loanfit.git
    cd loanfit
    ```

2. Create a virtual environment and activate it:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. **Exploratory Data Analysis:**
   - Run the `EDA.py` script to perform initial data analysis.
    ```bash
    python EDA.py
    ```

2. **Data Preprocessing and Model Training:**
   - Use the `dataset.py` script to load, preprocess the data, and train the machine learning model.
    ```bash
    python dataset.py
    ```

3. **Model Evaluation:**
   - Evaluate the trained model using the `test_data.csv` dataset to check the accuracy and performance metrics.

## Results
The project demonstrates a high prediction accuracy for loan eligibility, utilizing effective data preprocessing techniques and optimized machine learning models. Detailed EDA results and model performance metrics are documented within the scripts.


