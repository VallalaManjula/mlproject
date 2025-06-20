## End to End MAchine Learning Project

# 🎓 Student Performance Prediction

This project understands how the student's performance (test scores) is affected by other variables such as Gender, Ethnicity, Parental level of education, Lunch and Test preparation course.

---

## 📁 Project Structure

```
mlproject/
├── notebook/
│   ├── data/
│   │   └── stud.csv
│   ├── 1. EDA STUDENT PERFORMANCE.ipynb
│   └── 2. MODEL TRAINING.ipynb
├── src/
│   ├── components/
│   ├── pipeline/
│   ├── __init__.py
│   ├── exception.py
│   ├── logger.py
│   └── utils.py
├── app.py
├── README.md
├── requirements.txt
└── setup.py
```

---

## 📊 Features

- Exploratory Data Analysis (EDA)
- Feature Engineering (Total Score, Average Score)
- Model Training using:
  - Linear Regression
  - Decision Tree Regressor
  - Random Forest Regressor
- Evaluation using R² Score
- Visualization of actual vs predicted values

---

## 📈 Dataset Information

The dataset includes the following columns:
- Gender
- Race/Ethnicity
- Parental Level of Education
- Lunch
- Test Preparation Course
- Scores: Math, Reading, Writing

New columns added:
- Total Score
- Average Score

---

## 🧠 Models and Performance

Three regression models were tested:

| Model                    | Accuracy (%) |
|--------------------------|--------------|
| **Linear Regression**    | **88.04**     |
| Random Forest Regressor  | 85.48         |
| Decision Tree Regressor  | 76.19         |

### ✅ Best Model: Linear Regression  
Linear Regression achieved the highest accuracy and generalization performance, making it the most suitable model for this dataset.

---

## 🛠️ Setup and Installation

1. Clone the repository:
```bash
git clone https://github.com/your-username/mlproject.git
cd mlproject
```

2. Create a virtual environment:
```bash
python -m venv venv
```

3. Activate the environment:
- On Windows:
```bash
venv\Scripts\activate
```
- On Unix or MacOS:
```bash
source venv/bin/activate
```

4. Install dependencies:
```bash
pip install -r requirements.txt
```

5. Launch the notebook:
```bash
jupyter notebook
```

---

## 📌 Usage

- Run `1. EDA STUDENT PERFORMANCE.ipynb` to explore and preprocess the data.
- Run `2. MODEL TRAINING.ipynb` to train and evaluate different models.

---

## 📌 Future Improvements

- Hyperparameter tuning using GridSearchCV
- Deployment using Streamlit or Flask
- Add more advanced regression models like XGBoost
- Add interactive visualizations

---

## 📬 Contact

For questions or suggestions, feel free to reach out via GitHub.

---

> *This project helps in understanding how the student's performance (test scores) is affected by other variables such as Gender, Ethnicity, Parental level of education, Lunch and Test preparation course.
