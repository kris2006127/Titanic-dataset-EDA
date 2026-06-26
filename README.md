#  Titanic Dataset Exploratory Data Analysis (EDA)

##  Project Overview

This project performs an Exploratory Data Analysis (EDA) on the famous Titanic dataset to understand the factors that influenced passenger survival. The analysis includes data inspection, missing value handling, feature engineering, survival analysis, and data visualization using Python.

---

##  Objectives

- Load and inspect the Titanic dataset.
- Analyze missing values and data types.
- Clean and preprocess the dataset.
- Analyze survival rates by:
  - Gender
  - Passenger Class
  - Age Groups
- Visualize findings using bar charts, boxplots, violin plots, and heatmaps.
- Generate key insights from the analysis.
- Export the cleaned dataset.

---

##  Dataset

The project uses the **Titanic Train Dataset** from Kaggle.

### Dataset Features

| Column | Description |
|---------|-------------|
| PassengerId | Passenger Identifier |
| Survived | Survival Status (0 = No, 1 = Yes) |
| Pclass | Passenger Class |
| Name | Passenger Name |
| Sex | Gender |
| Age | Passenger Age |
| SibSp | Number of Siblings/Spouses Aboard |
| Parch | Number of Parents/Children Aboard |
| Ticket | Ticket Number |
| Fare | Ticket Fare |
| Cabin | Cabin Number |
| Embarked | Port of Embarkation |

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

##  Project Workflow

### 1. Data Loading
- Load Titanic dataset
- Inspect dataset structure
- Display summary statistics

### 2. Data Cleaning
- Identify missing values
- Fill missing Age values using median
- Fill missing Embarked values using mode
- Remove Cabin column due to excessive missing values

### 3. Exploratory Data Analysis
- Overall survival rate
- Survival by gender
- Survival by passenger class
- Survival by age groups
- Passenger class distribution
- Fare distribution

### 4. Data Visualization
- Missing Values Heatmap
- Survival by Gender (Bar Chart)
- Survival by Passenger Class (Bar Chart)
- Survival by Age Group (Bar Chart)
- Age Distribution (Box Plot)
- Age Distribution (Violin Plot)
- Correlation Heatmap

### 5. Export Results
- Save cleaned dataset as CSV
- Generate insights report

---

##  Visualizations

- Missing Values Heatmap
- Survival Rate by Gender
- Survival Rate by Passenger Class
- Survival Rate by Age Group
- Age Distribution Boxplot
- Age Distribution Violin Plot
- Passenger Class Distribution
- Fare Distribution
- Correlation Heatmap

---

##  Key Insights

- Female passengers had significantly higher survival rates than male passengers.
- First-class passengers were more likely to survive than passengers in lower classes.
- Children had better survival rates compared to adults and seniors.
- Passenger class and gender were the strongest factors influencing survival.
- Most missing values were found in the Cabin column, which was removed during preprocessing.

---

##  Project Structure

```
Titanic-EDA/
│
├── train.csv
├── titanic_cleaned.csv
├── Titanic_EDA.ipynb
├── README.md
├── requirements.txt
├── LICENSE
└── visuals/
    ├── missing_values.png
    ├── survival_gender.png
    ├── survival_class.png
    ├── survival_age.png
    ├── boxplot.png
    ├── violinplot.png
    └── correlation_heatmap.png
```

---

##  Installation

Clone the repository:

```bash
git clone https://github.com/your-username/titanic-survival-analysis.git
```

Navigate to the project directory:

```bash
cd titanic-survival-analysis
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
Titanic_EDA.ipynb
```

---

##  Requirements

```
pandas
numpy
matplotlib
seaborn
jupyter
```

---

##  Learning Outcomes

Through this project, I gained practical experience in:

- Exploratory Data Analysis (EDA)
- Data Cleaning and Preprocessing
- Missing Value Handling
- Data Visualization
- Statistical Analysis
- Feature Engineering
- Python Data Analysis Libraries

---

##  License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

G V Grisha
