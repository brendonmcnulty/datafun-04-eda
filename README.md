# datafun-04-eda
# DataFun-04-Notebooks

## Author
Brendon McNulty

## Purpose
This project demonstrates the use of Jupyter Notebooks for Exploratory Data Analysis (EDA).  
It focuses on using **pandas**, **seaborn**, and **matplotlib** to explore datasets, generate statistics, and create visualizations.  
The primary dataset for this module is the Iris dataset, a classic dataset in data science.

## Project Organization

```text
🗂 Project Structure
.
├── brendon_eda_notebook.ipynb   # Main Jupyter Notebook for Exploratory Data Analysis
├── brendon_data/                # (Optional) Folder for datasets if added later
│   └── iris.csv                 # Example dataset (if needed locally)
├── .gitignore                   # Git ignore rules
├── requirements.txt             # Python dependencies
└── README.md                    # Project overview and documentation
```

## Notebook Checklist

- [] Notebook has exactly one Markdown title (with a single hash).
- [] Notebook has useful Markdown header cell with author and purpose, and date.
- [] Notebook uses numbered second-level Markdown headings for organization.
- [] Notebook has numbered sections with useful content for:
  - [] 1. Imports
  - [] 2. Load Data
  - [] 3. Initial Data Inspection
  - [] 4. Initial Descriptive Statistics
  - [] 5a. Initial Data Distribution for Numerical Columns
  - [] 5b. Initial Data Distribution for Categorical Columns
  - [] 6. Initial Data Transformation and Feature Engineering
  - [] 7. Initial Visualizations
  - [] 8. Initial Insights
  - [] 9. Storytelling and Presentation
- [] Notebook includes commentary after each section that tells a data story.
- [] Code and visuals are working, notebook is fully executed and on display in GitHub.

## Getting Started
1. Clone the repository from GitHub.
2. Create and activate a virtual environment:
   ```bash
   python -m venv .venv
   source .venv/bin/activate   # Mac/Linux
   .\.venv\Scripts\activate    # Windows PowerShell
   ```
3. Install the dependencies:
   ```bash
   pip install --upgrade pip setuptools wheel
   pip install -r requirements.txt
   ```
4. Open the notebook in VS Code or JupyterLab and select the correct Python kernel.

## Usage
- Run the cells in `brendon_eda_notebook.ipynb` step by step.
- Review commentary after each section for explanations and insights.
- Use this as a model for building clear, story-driven data analysis notebooks.

## License
This project is for educational purposes as part of the Data Analytics Fundamentals course.

