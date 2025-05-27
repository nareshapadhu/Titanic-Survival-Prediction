🚢 Titanic Survival Prediction
This project is a machine learning implementation to predict survival on the Titanic using the famous Titanic dataset from Kaggle. It uses data preprocessing, feature engineering, and Logistic Regression to predict whether a passenger survived or not.


📊 Dataset
The dataset includes information such as:

Passenger Class (Pclass)

Name, Sex, Age

Number of Siblings/Spouses aboard (SibSp)

Number of Parents/Children aboard (Parch)

Ticket number, Fare

Cabin, Embarked location

Survived (Target)

📌 Features Used
After preprocessing, the model uses the following features:

Pclass

Sex

Age

SibSp

Parch

Fare

Embarked

Missing values are handled using imputation techniques:

Age: Filled with median

Embarked: Filled with mode

Fare: Filled with median

Categorical features like Sex and Embarked are encoded using LabelEncoder.

🧠 Model Used
Logistic Regression from scikit-learn

n_estimators: 100

criterion: 'entropy'

random_state: 0

Accuracy achieved on the test set: ~81.56%

🛠️ Installation
Clone the repository:

bash
Copy
Edit
git clone https://github.com/yourusername/titanic-survival-prediction.git
cd titanic-survival-prediction
Install the required packages:

bash
Copy
Edit
pip install -r requirements.txt
If requirements.txt isn't included, install manually:

bash
Copy
Edit
pip install pandas numpy scikit-learn matplotlib seaborn
Run the notebook:

bash
Copy
Edit
jupyter notebook "Titanic Survival Prediction.ipynb"
📈 Output
The model provides:

Accuracy score

Confusion matrix

Heatmap visualization

Prediction on test set

📄 License
This project is licensed under the MIT License.

🤝 Contributing
Feel free to fork the repo, open issues, or submit PRs!