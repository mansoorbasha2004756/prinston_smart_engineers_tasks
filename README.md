# Prinston Data Science Internship Tasks

This repository contains the tasks completed as part of the **Prinston Data Science Internship**. Each task explores a different data science concept, from supervised machine learning classification to exploratory data analysis on real-world socioeconomic data.

## 📁 Repository Structure

```
codealpha_tasks/
│
├── Task1_Iris_Flower_Classification/
│   ├── iris_classification.ipynb   # or .py
│   ├── dataset (if applicable)
│   └── README.md (optional task-level notes)
│
├── Task2_Unemployment_Analysis/
│   ├── unemployment_analysis.ipynb # or .py
│   ├── dataset(s) used
│   └── README.md (optional task-level notes)
│
└── README.md
```

> Update the folder/file names above to match your actual repo layout.

---

## 🌸 Task 1: Iris Flower Classification

### Overview
A machine learning classification project that identifies the species of an Iris flower — **Setosa**, **Versicolor**, or **Virginica** — based on its physical measurements.

### Objective
- Use measurements of Iris flowers (sepal length, sepal width, petal length, petal width) as input features.
- Train a machine learning model to classify the flower species based on these measurements.
- Evaluate the model's accuracy and performance using test data.
- Understand fundamental classification concepts in machine learning.

### Tech Stack / Libraries
- **Python**
- **Scikit-learn** — dataset access, model building, and evaluation
- **Pandas** — data handling
- **NumPy** — numerical computation
- **Matplotlib / Seaborn** — data visualization

### Approach
1. Loaded the Iris dataset (via `sklearn.datasets` or CSV).
2. Performed exploratory data analysis (EDA) to understand feature distributions and relationships.
3. Split the data into training and testing sets.
4. Trained a classification model (e.g., Logistic Regression / K-Nearest Neighbors / Decision Tree / SVM).
5. Evaluated performance using metrics such as accuracy, confusion matrix, and classification report.

### Results
The trained model successfully classifies Iris flowers into their respective species with high accuracy, demonstrating a solid understanding of supervised classification workflows.

---

## 📉 Task 2: Unemployment Analysis with Python

### Overview
An exploratory data analysis (EDA) project examining unemployment trends in the context of the **COVID-19 pandemic**, uncovering key patterns and their broader economic and social implications.

### Objective
- Analyze the impact of COVID-19 on unemployment rates.
- Identify key trends and patterns in the unemployment data over time.
- Draw insights connecting these trends to economic and social policy implications.

### Tech Stack / Libraries
- **Python**
- **Pandas** — data cleaning and manipulation
- **NumPy** — numerical analysis
- **Matplotlib / Seaborn / Plotly** — data visualization

### Approach
1. Collected and cleaned unemployment rate data (pre- and post-COVID periods).
2. Performed time-series analysis to observe how unemployment rates shifted during the pandemic.
3. Visualized trends across regions/states/sectors (as applicable) to highlight disparities.
4. Interpreted findings in relation to economic disruptions and policy responses.

### Key Insights
- Unemployment rates spiked sharply during the onset of COVID-19 lockdowns.
- Recovery patterns varied across regions/sectors.
- The analysis highlights the importance of timely economic and social policy interventions during crises.

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/mansoorbasha2004756/prinston_smart_engineers_tasks.git
   cd prinston_smart_engineers_tasks
   ```

2. Install the required dependencies:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```

3. Navigate to the desired task folder and run the notebook or script:
   ```bash
   jupyter notebook Task1_Iris_Flower_Classification/iris_classification.ipynb
   ```

---

## 🎓 About Prinston smart engineers

This project was completed as part of the **Printson Data Science Internship**, aimed at providing hands-on experience with real-world data science problems, from machine learning classification to exploratory data analysis.

## 📌 Status

✅ Task 1: Iris Flower Classification — **Completed**
✅ Task 2: Unemployment Analysis with Python — **Completed**

## 📄 License

This project is open source and available for educational purposes.
