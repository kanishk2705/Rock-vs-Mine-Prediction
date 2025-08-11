# Rock-vs-Mine-Prediction

# Sonar Rock vs Mine Classification

-- This project uses a Logistic Regression model to classify sonar signals as Rock (R) or Mine (M) based on 60 features from the Sonar Dataset (Kaggle Dataset Repository).

# 📌 Project Overview
The goal of this project is to:
-- Build a machine learning model to distinguish between sonar signals from rocks and mines.
-- Train the model using logistic regression.
-- Evaluate the model's performance using accuracy score and confusion matrix.

# 🛠 Technologies Used
-- Python 3.x
-- Pandas
-- NumPy
-- scikit-learn

# 📂 Project Structure
.
├── sonar_model.py # Main model training and evaluation script
├── requirements.txt      # Python dependencies
|-- sonar_model.ipynb     # jupyter notebook
├── sonar.csv             # Dataset
├── README.md             # Project documentation

# 📊 Dataset
Source: Kaggle Dataset
Instances: 208 samples
Features: 60 numerical attributes representing sonar signal energy at different frequencies.
Target: R (Rock) or M (Mine)

# ⚙️ Installation
Clone the repository:

git clone https://github.com/your-username/sonar-rock-vs-mine.git
cd sonar-rock-vs-mine

Install dependencies:
pip install -r requirements.txt

Run the model:
python sonar_model.py

# 📈 Model Evaluation
The script provides:
Accuracy Score (for both training and test dataset)
Accuracy: 85%

# 🔮 Future Improvements
-- Try other algorithms like Random Forest, SVM, or Neural Networks.
-- Perform hyperparameter tuning.
-- Use cross-validation for more robust performance measurement.

# 📜 License
This project is open-source under the MIT License.
