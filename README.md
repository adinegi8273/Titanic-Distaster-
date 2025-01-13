# Titanic Survival Prediction Project 🚢

## Overview  
<p>
This project leverages machine learning techniques to predict the survival of passengers aboard the RMS Titanic, based on various attributes like <strong>age</strong>, <strong>gender</strong>, <strong>class</strong>, and <strong>fare</strong>. Using <strong>Python</strong> and key libraries such as <em>NumPy</em>, <em>Pandas</em>, <em>Matplotlib</em>, <em>Seaborn</em>, <em>Scikit-learn</em>, and <em>XGBoost</em>, the study performs a comprehensive analysis to identify significant factors influencing survival rates. The project also compares the performance of three machine learning models: <strong>Logistic Regression</strong>, <strong>Random Forest</strong>, and <strong>XGBoost</strong>, evaluating their <strong>accuracy</strong>, <strong>precision</strong>, and <strong>recall</strong>.
</p>

---

## Features  
<ul>
  <li>📊 <strong>Data Analysis</strong>: Performed exploratory data analysis (EDA) to understand patterns and correlations in the dataset.</li>
  <li>🛠️ <strong>Data Preprocessing</strong>: Handled missing values, removed irrelevant fields, and encoded categorical variables for better model performance.</li>
  <li>⚙️ <strong>Model Implementation</strong>: Built models using <em>Logistic Regression</em>, <em>Random Forest</em>, and <em>XGBoost</em>.</li>
  <li>📈 <strong>Performance Metrics</strong>: Evaluated the models based on <strong>accuracy</strong>, <strong>precision</strong>, and <strong>recall</strong>.</li>
  <li>🔍 <strong>Insights</strong>: Identified significant factors affecting survival, such as gender, class, and age.</li>
</ul>

---

## Technologies Used  
<ul>
  <li><strong>Python</strong></li>
  <li><em>Libraries:</em> NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn, XGBoost</li>
  <li><strong>Data Source:</strong> <a href="https://www.kaggle.com/">Kaggle</a></li>
</ul>

---

## Results  
<p>
The project concludes with a comparative analysis of the models used. The results are summarized below:
</p>
<table>
  <thead>
    <tr>
      <th>Model</th>
      <th>Accuracy</th>
      <th>Precision</th>
      <th>Recall</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Logistic Regression</td>
      <td>76.24%</td>
      <td>75.80%</td>
      <td>76.24%</td>
    </tr>
    <tr>
      <td>Random Forest</td>
      <td>75.40%</td>
      <td>74.50%</td>
      <td>74.80%</td>
    </tr>
    <tr>
      <td>XGBoost</td>
      <td>77.78%</td>
      <td>78.10%</td>
      <td>75.00%</td>
    </tr>
  </tbody>
</table>

---

## Insights  
<ul>
  <li>🚺 <strong>Gender</strong>: Females had a significantly higher survival rate compared to males.</li>
  <li>🎫 <strong>Class</strong>: Passengers in first class were more likely to survive due to better access to lifeboats.</li>
  <li>🧒 <strong>Age</strong>: Children were prioritized for evacuation, increasing their survival rate.</li>
</ul>

---

## Future Enhancements  
<ul>
  <li>🔄 Use more robust techniques for handling missing data.</li>
  <li>🤝 Combine models (e.g., Random Forest for feature selection and XGBoost for final predictions).</li>
  <li>📊 Apply neural networks for handling larger datasets.</li>
</ul>

---
