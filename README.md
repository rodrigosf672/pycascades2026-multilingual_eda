# To Notebook or Not to Notebook: Multilingual Workflows for EDA

Demo materials for PyCascades 2026 talk on multilingual workflows in exploratory data analysis.

**Talk**: Saturday, March 21, 4:15 PM | Fletcher Auditorium

## Overview

This repository demonstrates how to run SQL, Python, and R in a single notebook environment, showcasing the power and challenges of multilingual workflows for data analysis.

## Files

- `multilingual_run_all_ready.ipynb` - Jupyter notebook demo (click "Run All")
- `multilingual_demo.qmd` - Quarto markdown equivalent

## Requirements

```bash
pip install ipython-sql prettytable==3.9.0 rpy2 pandas numpy scikit-learn
```

## Usage

**Jupyter Notebook:**
```bash
jupyter notebook multilingual_run_all_ready.ipynb
```

**Quarto:**
```bash
quarto preview multilingual_demo.qmd
```

## About the Talk

Explores how multilingual workflows transform EDA, highlighting where notebooks shine and where they introduce challenges around testing, version control, and scaling. Practical strategies for integrating multiple languages while maintaining trust and integrity in data science workflows.

## License

MIT License - See [LICENSE](LICENSE) file for details.
