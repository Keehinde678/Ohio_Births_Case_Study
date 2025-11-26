# Ohio_Births_Case_Study

This repository contains a detailed statistical analysis of Ohio birth records. The project aims to explore patterns in birth outcomes across demographic and clinical factors, using advanced statistical models and reproducible workflows.

---

## Project Overview

The Ohio_Births_Case_Study project includes:

* **Data preprocessing:** Cleaning and structuring raw birth records for analysis.
* **Statistical analysis:** Using random effects models to examine patterns in birth outcomes.
* **Visualizations:** Plots and charts to summarize findings and highlight key trends.
* **Documentation:** Detailed explanations of methods, results, and scripts.

This project showcases reproducible research practices and demonstrates competency in statistical modeling, data management, and visualization.

---

## Project Structure

* `data/` : Contains raw and processed datasets (note: large CSV files tracked with Git LFS).
* `scripts/` : Python or R scripts used for data cleaning, analysis, and visualization.
* `outputs/` : Generated analysis results, plots, and summaries.
* `requirements.txt` : Python dependencies for reproducing the analysis.
* `README.md` : Overview of the project, setup instructions, and context.

---

## Statistical Methods

The analysis primarily uses **random effects models** to account for:

* Variability across different hospitals and regions
* Potential correlations between repeated measures for the same mother or hospital
* Differences across demographic groups while adjusting for confounding variables

This approach allows for robust estimation of the effects of predictors on birth outcomes while accounting for hierarchical structures in the data.

---

## How to Reproduce the Analysis

1. Clone the repository:

```bash
git clone https://github.com/keehinde678/Ohio_Births_Case_Study.git
cd Ohio_Births_Case_Study
```

2. Install Python dependencies:

```bash
pip install -r requirements.txt
```

3. Make sure Git LFS is installed to handle the large data file:

```bash
git lfs install
git lfs pull
```

4. Run the scripts in the `scripts/` directory in order, starting with data preprocessing and ending with visualizations.

---

## Author

Kehinde Soetan
[GitHub Profile](https://github.com/keehinde678)

---

## Notes

* This project demonstrates reproducible research workflows and proper handling of large data files with Git LFS.
* All results are reproducible using the scripts and data in this repository.
* Citations and references to Ohio birth datasets are included within the scripts where applicable.
