
# MLOps Pipeline Implementation

##  Overview

This project demonstrates a basic MLOps pipeline workflow implemented using Python. It covers the essential stages of a Machine Learning project from data preprocessing to model training, evaluation, and logging.

##  Key Components

- Data Ingestion: Loading dataset from a CSV file using Pandas.
- Data Splitting: Dividing data into training and testing sets using `train_test_split`.
- Model Training: Using `LogisticRegression` to train a simple classification model.
- Model Evaluation: Evaluating the trained model using accuracy score.
- Model Saving: Persisting the model with `joblib`.
- MLflow Logging: Logging experiment details such as parameters, metrics, and model artifacts.

##  Technologies Used

- Python
- Pandas
- Scikit-learn
- Joblib
- MLflow

##  Project Structure

.
├── dataset.csv  
├── mlops_pipeline.ipynb  
├── model.pkl  
└── README.md  

##  How to Run

1. Clone the repository:
   git clone https://github.com/Darshan-sk24/mlops-foundation
2. Install required dependencies:
3. Run the notebook:
4. Optional: Run MLflow UI to view logs:
   

##  Output

- Trained model saved as `model.pkl`
- Metrics such as Accuracy are logged
- MLflow logs contain run details and model artifacts

##  Notes

- Make sure `mlflow` is installed and properly set up.
- You may change the classifier or dataset to experiment with different models.

##  Author

Darshan S K
