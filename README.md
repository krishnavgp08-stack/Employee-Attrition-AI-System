# Employee Attrition AI System

[![GitHub](https://img.shields.io/badge/GitHub-Repo-blue)](https://github.com/krishnavgp08-stack/Employee-Attrition-AI-System)
[![Python](https://img.shields.io/badge/Python-3.8+-green)](https://python.org)
[![ML](https://img.shields.io/badge/ML-Scikit--learn-orange)](https://scikit-learn.org)

> An AI-powered system for employee attrition analysis, prediction, and retention strategies using Machine Learning, NLP, and Power BI.

---

## 📋 Project Overview

This project leverages **Machine Learning** and **Natural Language Processing** to predict employee attrition, identify key factors influencing turnover, and build interactive Power BI dashboards for HR analytics and decision-making.

The system helps organizations:
- Predict which employees are at risk of leaving
- Understand key drivers of attrition
- Design targeted retention strategies
- Visualize workforce trends through interactive dashboards

---

## 📁 Repository Structure

```
Employee-Attrition-AI-System/
├── .gitignore              # Git ignore rules
├── IBM Employee Attrition & Performance.csv  # Dataset
├── MySQL Codes/            # Database queries and schemas
├── Notebooks/              # Jupyter notebooks with analysis
├── PowerBI/                # Power BI dashboard files
├── README.md               # Project documentation
├── Requirements.txt        # Python dependencies
└── Scripts/                # Python scripts for ML pipeline
```

---

## 🛠️ Technologies Used

| Category | Tools & Technologies |
|----------|---------------------|
| **Programming** | Python, SQL, MySQL |
| **Machine Learning** | Scikit-learn, Pandas, NumPy |
| **NLP** | Natural Language Processing |
| **Visualization** | Power BI, Matplotlib, Seaborn |
| **Version Control** | Git, GitHub |

---

## 📊 Features

- **Data Preprocessing**: Cleaning and transformation of IBM Employee Attrition dataset
- **Exploratory Data Analysis (EDA)**: Statistical insights into employee demographics, job satisfaction, and attrition patterns
- **Machine Learning Models**: Classification algorithms for attrition prediction (Logistic Regression, Random Forest, Decision Trees, etc.)
- **Model Evaluation**: Accuracy, Precision, Recall, F1-Score, ROC-AUC analysis
- **Feature Importance**: Identification of key factors driving attrition
- **Power BI Dashboard**: Interactive visualization of attrition trends, department-wise analysis, and predictive insights
- **MySQL Integration**: Database storage and querying for employee data

---

## 🚀 Getting Started

### Prerequisites

- Python 3.8 or higher
- Jupyter Notebook
- Power BI Desktop (for dashboard viewing)
- MySQL Server (optional, for database features)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/krishnavgp08-stack/Employee-Attrition-AI-System.git
cd Employee-Attrition-AI-System
```

2. Install dependencies:
```bash
pip install -r Requirements.txt
```

3. Open the notebooks in the `Notebooks/` folder and run the cells sequentially.

---

## 📈 Model Performance

The ML models in this project are evaluated on the following metrics:

| Metric | Description |
|--------|-------------|
| **Accuracy** | Overall correctness of predictions |
| **Precision** | True positives among predicted positives |
| **Recall** | True positives among actual positives |
| **F1-Score** | Harmonic mean of Precision and Recall |
| **ROC-AUC** | Area under the ROC curve |

---

## 💡 Key Insights

Through analysis of the IBM Employee Attrition dataset, the following factors were identified as significant predictors of attrition:

- **OverTime**: Employees working overtime show higher attrition rates
- **Monthly Income**: Lower income correlates with higher attrition risk
- **Job Satisfaction**: Low job satisfaction is a strong predictor
- **Years at Company**: Employees with fewer years show higher turnover
- **Work-Life Balance**: Poor work-life balance increases attrition likelihood

---

## 📚 Future Enhancements

- [ ] Deploy the model as a web application (Streamlit/Flask)
- [ ] Add real-time prediction API
- [ ] Integrate with HRIS systems for live data
- [ ] Extend to include employee sentiment analysis
- [ ] Build automated retention recommendation engine

---

## 📄 License

This project is open source and available for educational and research purposes.

---

## 👤 Author

**Krishnakumar K**  
📧 krishnavgp08@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/krishnakumar-hr)  
📂 [GitHub Profile](https://github.com/krishnavgp08-stack)

---

<div align="center">
  <strong>If you found this project helpful, please ⭐ star the repository!</strong>
</div>
