# COLLEGE BASKETBALL TEAMS PERFORMNCE CLASSIFICATION  DATASET.

### Project Description.

- This project analyses college basketball team statistics to classify 
and predict team performance using various machine learning 
classification algorithms. The dataset contains seasonal performance 
metrics including points scored, rebounds, assists and turnovers

### Technologies Used.

- Python
- Pandas
- Matplotlib
- Scikit-Learn 
- NumPy

### Project Structure
```
ML_Project/
│
├── data/
│   └── cbb.csv                  # College Basketball dataset
│
├── notebooks/
│   └── ml_analysis.ipynb        # Main analysis notebook
│
├── outputs/
│   ├── visualizations/          # Charts and graphs
│   │   ├── data_distribution.png
│   │   ├── feature_correlation.png
│   │   └── model_comparison.png
│   │
│   └── results/                 # Model results
│       └── model_rankings.csv   # Classifier comparison table
│
├── .gitignore
├── requirements.txt
└── README.md
```
### Project Set Up.

#### 1. Clone the Repo.

`git clone git@github.com:<username>/ML_Project.git`
`cd ML_Project`

#### 2. Create the Virtual Environment.

**Ubuntu/Mac**

`python3 -m venv .venv`
`source .venv/bin/activate`

**Windows**

`python -m venv .venv`
`.venv\Scripts\activate.ps1`

#### 3. Install Dependancies

`pip install -r requirements.txt`


