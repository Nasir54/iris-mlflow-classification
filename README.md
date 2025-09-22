# Iris Classification with MLflow Tracking 🌸

This project demonstrates **Iris flower classification** using Logistic Regression with **MLflow** for experiment tracking, model logging, and versioning.  

## 🚀 Features
- Train a Logistic Regression classifier on the Iris dataset.  
- Track experiments, parameters, and metrics using **MLflow Tracking**.  
- Log and register models with **MLflow Model Registry**.  
- Compare different runs in the **MLflow UI**.  
- Save dependencies in `requirements.txt` for reproducibility.  

---

## 📂 Project Structure
Iris-MLflow-Classification/
│── iris_mlflow.ipynb # Main Jupyter notebook
│── requirements.txt # Project dependencies
│── mlruns/ # MLflow tracking data (auto-generated)
│── models/ # MLflow registered models (auto-generated)
│── mlflow_venv/ # Virtual environment (not needed in repo)
└── README.md # Project documentation


---

## ⚙️ Installation

1. Clone the repo:
   ```bash
   git clone https://github.com/Nasir54/iris-mlflow-classification.git
   cd iris-mlflow-classification

2. Create a virtual environment:

python3 -m venv venv
source venv/bin/activate   # On Mac/Linux
venv\Scripts\activate      # On Windows

3. Install dependencies:

pip install -r requirements.txt

▶️ Usage

Start the MLflow UI:

mlflow ui --backend-store-uri ./mlruns


Open http://127.0.0.1:5000
 to view experiments.

Run the notebook:

Open iris_mlflow.ipynb in Jupyter/VS Code.

Train the model.

View logged parameters, metrics, and models in MLflow UI.

📊 Example Output

Accuracy: 100% (on Iris dataset)

Registered Model: IrisLogisticRegressionModel