📚 Student Score Prediction Model using Linear Regression

This project predicts study hours based on previous exam scores using Linear Regression and compares it with Polynomial Regression (Degree 2 & 3) for better accuracy.

✅ Project Overview

The main objective of this project is to analyze the relationship between previous exam scores and study hours and build a predictive model using machine learning regression techniques. The model evaluates:

Linear Regression

Polynomial Regression (Degree 2 & 3)

Finally, it selects the best-performing model based on R² score and visualizes the predictions against actual data.

🛠️ Technologies Used

Python 3

Pandas (Data handling)

NumPy (Mathematical operations)

Matplotlib (Data visualization)

Scikit-learn (Machine Learning)

📂 Dataset

The dataset used in this project is:
student_exam_data.csv
It contains the following columns:

Previous Exam Score → Previous exam performance

Study Hours → Study hours for the current exam

🔍 Features

✔ Predict study hours based on previous exam score
✔ Implements Linear Regression and Polynomial Regression
✔ Evaluates models using:

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

R² Score
✔ Visual Comparison of Linear vs Polynomial Regression

📊 Model Evaluation

The project compares:

Linear Regression

Polynomial Regression (Degree 2)

Polynomial Regression (Degree 3)

Selects the best polynomial model based on R² score.

📈 Visualization

The script generates two plots:

Linear Regression: Prediction vs Actual

Polynomial Regression (Best Degree): Prediction vs Actual

▶️ How to Run

Clone this repository:

git clone https://github.com/shazimjaved/student-score-prediction.git


Navigate to the project folder:

cd student-score-prediction


Install dependencies:

pip install -r requirements.txt


Add the dataset student_exam_data.csv in the same directory.

Run the script:

python main.py

✅ Example Output (Console)
----- Linear Regression -----
Mean Absolute Error: X.XX
Mean Squared Error: X.XX
Root Mean Squared Error: X.XX
R² Score: 0.XXXX

Best Polynomial Model: Degree 3
----- Polynomial Regression (Best) -----
Mean Absolute Error: X.XX
Mean Squared Error: X.XX
Root Mean Squared Error: X.XX
R² Score: 0.XXXX

📷 Graph Example

Linear vs Polynomial Regression

Blue dots → Actual data

Red line → Linear Regression

Orange line → Polynomial Regression

📌 Future Enhancements

Include train-test split for better evaluation

Deploy model using Flask or Streamlit

Add real-world student data for predictions

📜 License

This project is open-source and available under the MIT License.