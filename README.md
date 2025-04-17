# Heart-attack-Prediction-with-logistic-
This project uses Logistic Regression to predict the risk of heart failure based on medical data. It allows interactive user input to check whether a patient has a high chance of a heart attack.

📌 Features
Machine learning model using Logistic Regression
Predicts risk of heart failure
Interactive input for new patient data
Option to check multiple patients
Displays prediction result in a friendly format
🧪 Dataset Features
The model uses the following 12 features to make predictions:

age
anaemia
creatinine_phosphokinase
diabetes
ejection_fraction
high_blood_pressure
platelets
serum_creatinine
serum_sodium
sex
smoking
time
The target variable is:

DEATH_EVENT: 1 indicates the patient died, 0 indicates survival.
🚀 How to Run
Clone or download the repository.
Make sure you have Python installed (3.7+ recommended).
Install the required packages:
pip install pandas numpy scikit-learn
Run the Python script:
python heart_predictor.py
Enter patient data in the terminal when prompted.
🧠 Example Prediction Output
Enter the age: 65
Anaemia (1 for yes, 0 for no): 0
...
🧠 Prediction Result:
⚠️ Heart attack chances are high.

Do you want to check another patient? (1 for Yes / 0 for No): 0
Exiting the system. Stay healthy! 🫀
📷 Optional: Show Image in Notebook
You can add a heart-related image in your Jupyter Notebook for presentation using:
from IPython.display import display, 
📁 File Structure
📦heart-disease-predictor
 ┣ 📄 heart_predictor.py
 ┣ 📄 README.md
 ┗ 📄 data.csv (or data variable inside script)
📚 Dependencies
numpy
pandas
scikit-learn
(optional for notebooks)IPython.display
Made with ❤️ by Basu sharma
Feel free to reach out for contributions, questions, or improvements.
