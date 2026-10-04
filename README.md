# Python Libraries Practice: NumPy, Pandas & Seaborn

Hands-on practice notebooks where I'm learning the core Python data analysis libraries by working with real datasets. This repo tracks my progress as I build the skills needed for a data analyst role.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C8CBF?style=flat-square)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

---

## Notebooks

| Notebook | What it covers |
|----------|----------------|
| [`python_libraries_practice-1.ipynb`](./python_libraries_practice-1.ipynb) | Python lists, pandas DataFrames, sorting and indexing, Seaborn visualizations |
| [`python_libraries_practice-2.ipynb`](./python_libraries_practice-2.ipynb) | Reading data from the web, combining multi-season data, conditional filtering and column creation |

---

## Topics Covered

### Notebook 1: Fundamentals and Visualization
- **Python basics:** list operations (`pop`, `del`, `sort`)
- **DataFrames:** creating them from NumPy arrays and dictionaries, custom row and column labels
- **Students Performance dataset:**
  - Creating a new `average` score column
  - Proportions with `value_counts(normalize=True)`
  - Multi-column and case-insensitive sorting
  - Setting a custom index and renaming columns
- **Seaborn on the Penguins dataset:**
  - Distributions: histogram, KDE, rug plot
  - Categorical plots: strip, swarm, box, violin, count
  - Relationships: scatter, regression, line, joint plot
  - Correlation heatmap and pair plot

### Notebook 2: Data Loading and Conditional Logic
- **Reading CSVs from a URL** with `pd.read_csv`
- **Mini web-data project:** loops that pull football data (Premier League, La Liga, Bundesliga and more) across multiple seasons into one dictionary of DataFrames using `pd.concat`
- **Laptop Price dataset:**
  - Filtering with conditions, `&` operators and `isin()`
  - Creating categories with `np.where` (two outcomes) and `np.select` (multiple outcomes)
  - Binning prices and screen sizes into tiers
  - Detecting duplicates with `duplicated()`

---

## Datasets Used

| Dataset | Source |
|---------|--------|
| Students Performance | [Kaggle](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams) |
| Laptop Price | [Kaggle](https://www.kaggle.com/datasets/muhammetvarli/laptop-price) |
| Football match data | [football-data.co.uk](https://www.football-data.co.uk/data.php) |
| Penguins | Built into Seaborn (`sns.load_dataset('penguins')`) |

---

## How to Run

```bash
# 1. Clone the repo
git clone https://github.com/YOUR-GITHUB-USERNAME/YOUR-REPO-NAME.git
cd YOUR-REPO-NAME

# 2. Install the libraries
pip install pandas numpy seaborn matplotlib jupyter

# 3. Launch Jupyter
jupyter notebook
```

Place the CSV files (`StudentsPerformance.csv`, `laptop_price.csv`) in the same folder as the notebooks before running them.

---

## Key Learnings
- Cleaning and transforming data with Pandas is most of the work; analysis comes after.
- `np.select` is cleaner than nested `if` logic for creating categories.
- Choosing the right plot type depends on whether the data is numeric or categorical.
- Automating data collection with loops saves a lot of manual work.

## What's Next
- [ ] Data cleaning on messy datasets (missing values, outliers)
- [ ] SQL analysis projects with MySQL
- [ ] Power BI dashboard from a real dataset
- [ ] End-to-end analysis project with written insights

---

## Connect
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Jaishree_Shukla-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jaishree-shukla-948496289)
