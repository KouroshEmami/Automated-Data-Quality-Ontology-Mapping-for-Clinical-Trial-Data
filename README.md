# Automated Data Quality & Ontology Mapping for Clinical Trial Data

## 📌 Overview
This project demonstrates the process of **cleaning, standardizing, and mapping** clinical trial data to a standard ontology (DrugBank).  
It includes automated **data quality checks**, **ontology mapping**, and **governance documentation** to ensure accuracy, completeness, and interoperability — key skills for data analyst roles in the **life sciences** industry.

## 🎯 Objectives
- Detect and resolve data quality issues (missing values, duplicates, invalid formats)
- Standardize terms using controlled vocabularies and ontology mapping
- Automate data quality checks using Python scripts
- Provide data governance guidelines for consistent data management
- Produce reports and dashboards for data quality monitoring

## 🛠 Tools & Technologies
- Python (pandas, fuzzywuzzy, matplotlib, seaborn)
- Jupyter Notebooks
- ReportLab (for PDF documentation)
- CSV for data exchange
- Controlled vocabularies (DrugBank, SNOMED, etc.)

## 📂 Project Structure
│
├── data/ # Raw dataset (clinical_trials_sample.csv)
├── notebooks and scripts/ # Step-by-step analysis notebooks
├── governance/ # Data governance documentation
└── README.md # Project description



## 📊 Process Workflow
1. **Data Cleaning** (`01_data_cleaning.ipynb`)
   - Inspect dataset
   - Handle missing values and duplicates
   - Normalize text and format dates
   - Calculate completeness score

2. **Ontology Mapping** (`02_ontology_mapping.ipynb`)
   - Load vocabulary from DrugBank
   - Apply fuzzy string matching to map intervention names
   - Assign match score and mapping status

3. **Reporting & Analysis** (`03_reporting.ipynb`)
   - Summarize mapping success rates
   - Visualize mapping statuses
   - Identify root causes of failed mappings
   - Export summary reports

4. **Governance Documentation** (`data_quality_guidelines.pdf`)
   - Required fields and formats
   - Data entry rules
   - Mapping rules
   - Review process

## 📈 Example Outputs
- **`clinical_trials_cleaned.csv`** → Cleaned dataset with completeness score
- **`mapping_results.csv`** → Mapped interventions with match scores
- **`mapping_summary_report.csv`** → Data quality metrics
- **`data_quality_guidelines.pdf`** → Governance rules and best practices
