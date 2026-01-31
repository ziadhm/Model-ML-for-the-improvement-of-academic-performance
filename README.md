# Student Performance Analysis - ML Project

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ziadhm/Model-ML-for-the-improvement-of-academic-performance/blob/main/Student_Performance_Analysis.ipynb)

A machine learning project that analyzes student performance data to identify key factors affecting exam scores and generates actionable recommendations for academic improvement.

## 🎯 Project Overview

This project uses machine learning to predict student exam scores based on various factors such as study hours, attendance, sleep patterns, and socioeconomic factors. The model provides data-driven recommendations to help students improve their academic performance.

## 📊 Dataset

- **File**: `StudentPerformanceFactors.csv`
- **Records**: 6,607 students
- **Features**: 20 factors including:
  - Study habits (Hours Studied, Attendance, Tutoring Sessions)
  - Personal factors (Sleep Hours, Physical Activity, Motivation Level)
  - Socioeconomic factors (Family Income, Parental Education, Access to Resources)
  - School factors (Teacher Quality, School Type, Distance from Home)
  - Target variable: Exam Score (0-100)

## ✨ Features

- **Comprehensive Data Analysis**: Statistical analysis and visualization of student performance factors
- **Multiple ML Models**: Comparison of Linear Regression, Random Forest, and Gradient Boosting
- **Predictive Modeling**: Accurate prediction of exam scores (99.68% R² score)
- **Personalized Recommendations**: Data-driven suggestions for performance improvement
- **Impact Analysis**: Quantitative assessment of each recommendation's potential impact

## 🚀 Getting Started

### Prerequisites

```bash
Python 3.7+
Jupyter Notebook or Google Colab
```

### Installation

1. Clone the repository:

```bash
git clone https://github.com/ziadhm/Model-ML-for-the-improvement-of-academic-performance.git
cd Model-ML-for-the-improvement-of-academic-performance
```

1. Install required packages:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Usage

**Option 1: Local Jupyter Notebook**

```bash
jupyter notebook Student_Performance_Analysis.ipynb
```

**Option 2: Google Colab** (Recommended)

- Click the "Open in Colab" badge above
- Run all cells in order (takes 1-2 minutes)

## 🤖 Models & Performance

| Model                 | Training R² | Test R²    | RMSE       | MAE        |
| --------------------- | ----------- | ---------- | ---------- | ---------- |
| Linear Regression     | 0.9891      | 0.9887     | 0.8211     | 0.6519     |
| Random Forest         | 0.9972      | 0.9832     | 1.0025     | 0.7963     |
| **Gradient Boosting** | **0.9972**  | **0.9968** | **0.4379** | **0.3465** |

**Best Model**: Gradient Boosting Regressor with **99.68% accuracy**

## 📈 Key Findings

### Top Factors Affecting Exam Scores

1. **Previous Scores** (correlation: 0.9834)
2. **Hours Studied** (correlation: 0.9704)
3. **Attendance** (correlation: 0.9548)
4. **Tutoring Sessions** (correlation: 0.7396)
5. **Sleep Hours** (correlation: 0.7086)

### Example Results

For a student with below-average performance:

- **Starting Score**: 57.38 points
- **After Implementing All Recommendations**: 75.11 points
- **Total Improvement**: +17.73 points (+30.89%)

### Recommended Interventions (by Impact)

1. Improve attendance (65% → 90%): **+7.83 points**
2. Increase study time (12 → 20 hrs/week): **+6.88 points**
3. Add tutoring sessions (0 → 3 per week): **+3.10 points**
4. Get more sleep (5 → 8 hours): **+1.65 points**
5. Boost motivation (Low → High): **+1.43 points**

## 🛠️ Technologies Used

- **Python 3.x**
- **pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing
- **Matplotlib & Seaborn** - Data visualization
- **scikit-learn** - Machine learning models and evaluation

## 📁 Project Structure

```
├── Student_Performance_Analysis.ipynb  # Main Jupyter notebook
├── StudentPerformanceFactors.csv       # Dataset
└── README.md                            # Project documentation
```

## 🔬 Methodology

1. **Data Exploration**: Statistical analysis and visualization
2. **Data Preprocessing**: Handling missing values, encoding categorical variables, feature scaling
3. **Model Training**: Testing multiple algorithms with cross-validation
4. **Model Evaluation**: Comparing performance metrics (R², RMSE, MAE)
5. **Prediction & Recommendations**: Testing interventions and measuring impact

## 📝 Use Cases

- **Educational Institutions**: Identify at-risk students and provide targeted support
- **Students**: Understand which factors most impact their academic success
- **Parents**: Data-driven guidance on supporting their children's education
- **Researchers**: Analyze patterns in student performance data

## 🤝 Contributing

Contributions are welcome! Feel free to:

- Report bugs
- Suggest new features
- Submit pull requests

## 📄 License

This project is open source and available for educational purposes.

## 👤 Author

**Ziad Hammoud**

- GitHub: [@ziadhm](https://github.com/ziadhm)

## 📧 Contact

For questions or feedback, please open an issue in the repository.

---

⭐ If you find this project helpful, please consider giving it a star!
