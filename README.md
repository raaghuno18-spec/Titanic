# Titanic Data Analysis (Project 1)-Pluto Academy AI & ML Internship Program
## Exploratory Data Analysis & Survivor Insights Report

Analysis and exploration of the Titanic passenger dataset, exploring factors that influenced survival outcomes during the 1912 maritime disaster.

---

## Dataset

**Source:** Titanic Passenger Dataset (Kaggle)

The dataset contains comprehensive information about passengers aboard the RMS Titanic:

- **Rows:** 891 passengers
- **Columns:** 12 features
- **Key Features:** PassengerId, Pclass (ticket class), Name, Sex, Age, SibSp (siblings/spouses), Parch (parents/children), Ticket, Fare, Cabin, Embarked, Survived

**Data Coverage:** Passenger manifest data from the Titanic's maiden voyage on April 15, 1912.

---

## Objective

Conduct an exploratory data analysis to understand the Titanic dataset and surface patterns in survival outcomes. This analysis aims to:

- Understand the distribution of passengers across different demographics
- Identify key factors correlated with survival
- Visualize survival patterns across passenger classes, age groups, and gender
- Deliver data-backed insights about the disaster's impact across different passenger segments

---

## Key Insights

1. **Class Hierarchy in Survival** — First-class passengers had significantly higher survival rates compared to second and third-class passengers, reflecting both proximity to lifeboats and evacuation priority.

2. **Gender Disparities** — A strong "women and children first" evacuation protocol is evident; female passengers had substantially higher survival rates across all age groups compared to males.

3. **Age Factor** — Younger passengers, particularly children, had higher survival rates. Older passengers faced lower survival chances across all classes.

4. **Fare as Proxy for Class** — Ticket fare correlates strongly with both passenger class and survival outcome, indicating socioeconomic status played a critical role.

5. **Embarkation Point Patterns** — The port of embarkation shows variation in passenger demographics and survival rates, potentially reflecting boarding order and lifeboat availability at different stations.

---

## Visualizations

The analysis includes multiple chart types to explore the data from different angles:

- **Line/Trend Charts** — Survival rates across continuous variables (age, fare)
- **Bar Charts** — Survival counts by passenger class and gender
- **Histograms** — Distribution of key metrics (age, fare, passenger count)
- **Scatter Plots** — Relationships between numeric features (age vs. fare)
- **Heatmaps** — Correlation matrices between features
- **Count Plots** — Categorical breakdowns of survival outcomes

---

## Tech Stack

- **Language:** Python 3
- **Data Processing:** Pandas · NumPy
- **Visualization:** Matplotlib · Seaborn
- **Notebook Environment:** Jupyter

---

## Repository Structure

```
Titanic/
├── README.md                              # This file
├── LICENSE                                # Project license
├── .gitignore                             # Git ignore rules
├── files/                                 # Data files directory
│   └── (CSV data files)
├── images/                                # Generated visualizations
│   └── (exported chart PNGs)
└── notebooks/                             # Jupyter notebooks
    └── Titanic.ipynb                # Main EDA analysis notebook
```

---

## How to Run

### Prerequisites
Ensure you have Python 3.7+ installed with the required packages.

### Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/raaghuno18-spec/Titanic.git
   cd Titanic
   ```

2. **Create a virtual environment (optional but recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
   Or install manually:
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

4. **Launch Jupyter and open the notebook:**
   ```bash
   jupyter notebook notebooks/Titanic.ipynb
   ```

5. **Run all cells** top to bottom to generate analysis, visualizations, and insights.

---

## Dependencies

- pandas
- numpy
- matplotlib
- seaborn
- jupyter

---

## Author
Raghavendra N O — Pluto Academy AI & ML Internship, Project 02

## License

See [LICENSE](LICENSE) file for details.

---

**Project:** Titanic Data Analysis  
**Status:** Complete  
**Last Updated:** 2024
