<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
</head>
<body>

<h1>🧠 Predictive Modelling for Early Detection of Strokes</h1>

<p>
  <strong>Author:</strong> Al-Jamil <br>
  <strong>Last Updated:</strong> 18 April 2025
</p>

<hr>

<h2>📌 Project Overview</h2>
<p>
  This project aims to develop a Machine Learning model that can predict the likelihood of a stroke in patients using various health and demographic parameters. Stroke is a life-threatening condition, and early detection can significantly improve patient outcomes. This predictive model can assist healthcare providers in prioritizing care and minimizing the risk of delayed treatment.
</p>

<hr>

<h2>📂 Dataset</h2>
<ul>
  <li><strong>Source:</strong> Brain Stroke Dataset (Kaggle / UCI)</li>
  <li><strong>Total Records:</strong> 4,981</li>
  <li><strong>Features:</strong> Gender, Age, Hypertension, Heart Disease, Marital Status, Work Type, Residence Type, Glucose Level, BMI, Smoking Status, Stroke</li>
</ul>

<hr>

<h2>🧪 Methodology</h2>
<ol>
  <li><strong>Data Cleaning:</strong> Handled missing values, dropped irrelevant features</li>
  <li><strong>EDA:</strong> Visualized class imbalance and feature distributions</li>
  <li><strong>Feature Engineering:</strong> Binned age, one-hot encoded categorical variables</li>
  <li><strong>Model Training:</strong> Trained Logistic Regression, SVM, KNN, Naive Bayes, Random Forest, Decision Tree</li>
  <li><strong>Evaluation:</strong> Measured accuracy; planned for ROC-AUC, F1-score in future work</li>
</ol>

<hr>

<h2>⚙️ Technologies Used</h2>
<ul>
  <li>Python (Pandas, NumPy, Matplotlib, Seaborn)</li>
  <li>Scikit-learn (Modeling, Preprocessing)</li>
  <li>Jupyter Notebook</li>
</ul>

<hr>

<h2>🖼️ Gallery</h2>
<h3>📌 Checking How Many People Are in The Data had a Stroke</h3>
<img src="https://github.com/user-attachments/assets/22d7019a-2588-4b2d-8995-c8d68d771aee" width="600" height="400">

<h3>📌 Checking the Categorical Feature of Gender</h3>
<img src="https://github.com/user-attachments/assets/8324799e-3c82-4f6d-9a61-34dff5dd971d" width="600" height="400">

<h3>📌 Categorical Feature of Hypertansion</h3>
<img src="https://github.com/user-attachments/assets/c7643c8a-5416-48f4-b8ba-205ada2da425" width="600" height="400">

<h3>📌 Categorical Feature of Heart Disease</h3>
<img src="https://github.com/user-attachments/assets/fa34f64c-0b3b-4cb3-a37a-cbbfda1901a3" width="600" height="400">

<h3>📌 Ordinal Feature of Smoking Status</h3>
<img src="https://github.com/user-attachments/assets/22516f91-f2a8-47fc-8089-c4134b5ad88d" width="600" height="400">

<h3>📌 Checking the Relationship between the Gender and Smoking Status on Stroke</h3>
<img src="https://github.com/user-attachments/assets/3135a980-4358-4835-8d0e-941831e94362" width="600" height="400">

<h3>📌 Continous Feature on Age</h3>
<img src="https://github.com/user-attachments/assets/b80b4a67-e56a-4320-a128-9e7557818195" width="600" height="400">

<h3>📌 Density of Smoke Status on The Average Glucose Level in Graphs</h3>
<img src="https://github.com/user-attachments/assets/82437dc2-6332-443d-a490-c67ad9423bae" width="600" height="400">

<h3>📌 Correlation Heatmap</h3>
<img src="https://github.com/user-attachments/assets/5af9136f-baa1-4668-a734-6525aef65647" width="600" height="400">

<h3>📌 Feature Engineering and Data Cleaning</h3>
<img src="https://github.com/user-attachments/assets/2b3304ef-62d7-4148-8e5f-e09b8b231af0" width="600" height="500">

<h3>🛠️ Training and Testing Accuracy for Models</h3>

<h3>📌 Average CV Mean Accuracy</h3>

<img src="https://github.com/user-attachments/assets/83c32f57-2d89-4bb6-b8a8-74e1284c2071" width="600" height="400">

<h3>📌 Confusion Matrix on Applied Testing Models</h3>
<img src="https://github.com/user-attachments/assets/17738fb3-6758-41cd-bdaa-ee67c0777ce9" width="600" height="400">

<h3>📌 Prediction Test</h3>
<img width="628" alt="image" src="https://github.com/user-attachments/assets/ed9cc893-f951-4b66-a07c-c6c9827b993b" />

<hr>

<h2>📈 Future Improvements</h2>
<ul>
  <li>Incorporate advanced evaluation metrics (F1, Precision, Recall, ROC-AUC)</li>
  <li>Address class imbalance with SMOTE or class weighting</li>
  <li>Hyperparameter tuning with GridSearchCV</li>
  <li>Deploy the model using Streamlit or Flask</li>
</ul>

<hr>
<h2>🚀 How to Run</h2>
<pre>
1. Clone the repository:
   git clone https://github.com/yourusername/stroke-prediction.git

2. Install dependencies:
   pip install -r requirements.txt

3. Run the notebook:
   Open the Jupyter Notebook and run all cells.
</pre>

<hr>

<h2>📬 Contact</h2>
<p>
  For questions or suggestions, feel free to contact me via GitHub or email: aljamil01754@gmail.com

</p>

</body>
</html>
