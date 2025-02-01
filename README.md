Credit Card Default Prediction using IBM Watson Studio
Overview
This project predicts whether a customer will default on their credit card payment using machine learning models built and deployed on IBM Watson Studio. The goal is to help financial institutions assess credit risk effectively.

Dataset
The dataset contains details of customer transactions, credit limits, past payment history, and demographics.
Target Variable: Default Payment (Yes/No)
Features Include:
Credit limit
Payment history
Bill amount
Demographic details (age, education, etc.)
Technologies Used
IBM Watson Studio: Model training and deployment
IBM AI Runtime Services: Running the ML pipelines
IBM AutoAI: Automated model selection and hyperparameter tuning
Libraries Used:
Scikit-learn (Machine Learning Models)
Pandas, NumPy (Data Processing)
Matplotlib, Seaborn (Visualization)
Model Selection
Multiple machine learning models were evaluated using IBM AutoAI, with the best models ranked based on accuracy.

Rank	Model Pipeline	Algorithm	Accuracy
1	Pipeline 6	Snap Random Forest	0.821
2	Pipeline 2	XGB Classifier	0.820
3	Pipeline 4	XGB Classifier	0.820
4	Pipeline 3	XGB Classifier HPO	0.820
5	Pipeline 8	Snap Random Forest	0.819
6	Pipeline 7	Snap Random Forest	0.819
7	Pipeline 1	XGB Classifier HPO	0.818
Results
The Snap Random Forest Classifier achieved the highest accuracy of 82.1%.
The K-S Chart was used to determine the best threshold for credit risk assessment.
Hyperparameter tuning (HPO) improved the performance of XGBoost models.
How to Run the Project
Clone the repository:
git clone https://github.com/your-username/credit-card-default-prediction.git
cd credit-card-default-prediction
Install dependencies:
pip install -r requirements.txt
Open IBM Watson Studio and upload the project files.
Run the Jupyter Notebook or execute the model using IBM AI Runtime Services.
Future Scope
Real-time Credit Scoring: Deploying as an API for real-time analysis.
Deep Learning Models: Experimenting with neural networks for improved accuracy.
Feature Interpretability: Using SHAP values to explain model predictions.
Contributors
Your Name - GitHub
Collaborators (if any)
License
This project is licensed under the MIT License - see the LICENSE file for details.

If you use this project, consider giving a ⭐ on GitHub!
