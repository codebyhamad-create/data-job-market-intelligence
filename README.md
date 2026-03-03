## Data Job Market Intelligence – 2026

This project analyzes real data job postings to answer the question: **“What skills actually get you hired in 2026?”**

### Repository Structure

- **data/**: Raw CSVs from Kaggle (`job_postings.csv`, `job_skills.csv`, `job_summary.csv`).
- **notebooks/**: Main analysis notebook `job_market_analysis.ipynb`.
- **reports/**: Written reports and exported figures.
  - **figures/**: PNGs generated from the notebook (skill frequencies, salary boxplots, etc.).

### Dataset Source

The data is sourced from Kaggle: `https://www.kaggle.com/datasets/asaniczka/data-science-job-postings-and-skills`.

### How to Run the Analysis

1. **Create and activate a virtual environment (recommended)**.
2. **Install Python dependencies**:

```bash
pip install -r requirements.txt
```

3. **Launch Jupyter** from the repository root:

```bash
jupyter notebook notebooks/job_market_analysis.ipynb
```

4. **Run all cells** in order to:

- Clean and enrich the raw job postings.
- Extract and standardize skills.
- Analyze salary, experience level, location, and remote work trends.
- Train a simple salary prediction model.
- Generate visualizations and business insights.

### Main Questions Answered

- **Most demanded skills** across data roles.
- **Salary vs. experience level** patterns.
- **Location-based salary differences**.
- **Remote vs. on-site trends**.
- **Tool popularity** (Python, SQL, Power BI, Tableau, etc.).
- **Strategic guidance for aspiring data professionals in 2026**.

### Author

Prepared by: **Hamadullah Rajper**

