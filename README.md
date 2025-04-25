Titanic Survival Prediction 🚢💻
Welcome to the Titanic Survival Prediction project! This machine learning model predicts whether a passenger survived the Titanic disaster using historical data from Kaggle.



Tools & Libraries Used 🧰
Python 🐍

pandas & NumPy 📈

Matplotlib, Seaborn & Plotly 📊

Scikit-learn 🧠

XGBoost ⚡

Google Colab 💻

Techniques Used ⚙️
Data Preprocessing

Exploratory Data Analysis (EDA)

Label Encoding & Feature Scaling

Train-Test Split

Model Building using:

Logistic Regression

Decision Tree

Random Forest

XGBoost

Evaluation using Accuracy, Confusion Matrix & Classification Report

How to Run ▶️
Clone the repo or open the Colab notebook.

Upload the archive.zip file containing the dataset.

Run the cells in order.

Check the output of each model and compare performance.

Sample Code Snippet 🧪
python
Copy
Edit
from sklearn.ensemble import RandomForestClassifier
model = RandomForestClassifier()
model.fit(X_train, y_train)
pred = model.predict(X_test)
print("Accuracy:", accuracy_score(y_test, pred))
Results 📌
Best accuracy achieved with: XGBoost

Feature importance shows Sex, Fare, and Pclass are highly influential.

Issues Faced ⚠️
KeyError while dropping non-existent columns.

✅ Fixed using condition to check if column exists before dropping.

Contribute 🤝
Fork the repo, improve the model or visualization, and submit a PR!

License 📄
Open source for learning and educational purposes.

Would you like me to generate a version of this as a downloadable .md file or integrate it into your code notebook too?
