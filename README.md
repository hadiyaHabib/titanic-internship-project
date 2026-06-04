# Titanic Dataset Analysis — Decodlabs Internship Project

This repository contains my **Data Science Internship Project (Task 1)** completed for **Decodlabs**.  
The project performs full end-to-end data analysis on the classic **Titanic Dataset**.

---

## Project Overview

| Task | Description |
|------|-------------|
| **Task 1** | Data Understanding — Load dataset, explore structure, identify features |
| **Task 2** | Data Cleaning & Preprocessing — Handle missing values, remove duplicates |
| **Task 3** | Data Analysis & Pattern Discovery — Statistics, outlier detection |
| **Task 4** | Data Visualization & Storytelling — Charts and visual insights |
| **Task 5** | Simple Predictive Model — Decision Tree Classifier for survival prediction |

---

## Project Structure

```
titanic-internship-project/
│
├── Decodlabs_task.ipynb     # Main Jupyter Notebook (all 5 tasks)
├── README.md                # Project documentation
└── .gitignore               # Files to ignore
```

---

## Dataset

- **Dataset:** Titanic Dataset (from Kaggle)
- **Target Variable:** `Survived` (0 = Did Not Survive, 1 = Survived)
- **Key Features:** `Pclass`, `Sex`, `Age`, `Fare`, `Embarked`, `SibSp`, `Parch`

> **Note:** The dataset file (`archive.zip` / `Titanic_Cleaned.csv`) is not included in this repo due to size.  
> Download it from [Kaggle Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset) and place it in the root folder.

---

## 🛠️ Technologies Used

- Python 3
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

---

## Key Insights

1. More passengers **died** than survived overall.
2. **Female passengers** had a significantly higher survival rate.
3. **First-class passengers** survived more often than 2nd or 3rd class.
4. Most passengers were **between 20–40 years old**.
5. **Ticket fare** and **passenger class** strongly influenced survival chances.



## Model Performance

| Model | Accuracy |
|-------|----------|
| Decision Tree Classifier | ~78–82% |

---

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/titanic-internship-project.git
   ```

2. Open the notebook:
   ```bash
   jupyter notebook Decodlabs_task.ipynb
   ```
   Or upload directly to **Google Colab**.

3. Download the Titanic dataset from Kaggle and place `archive.zip` in the project folder.

4. Run all cells in order (Task 1 → Task 5).

## Author
**Hadia Habib** 
Data Science Intern @ Decodlabs  
 [hadiyach917@gmail.com]  
 [www.linkedin.com/in/hadiya-ch-752b9739a]


## 📄 License

This project is for educational and internship purposes only.
