# Student-Performance-DataSet-Preprocessing
A data preprocessing project using Python, Pandas, and Scikit-learn to clean and prepare the Students Performance in Exams dataset through missing value handling, duplicate removal, outlier detection, manual one-hot encoding, feature engineering, and feature scaling.


# Student Performance Data Preprocessing

## Overview

This project focuses on preprocessing the Students Performance in Exams dataset using Python and popular data science libraries. The goal is to understand the dataset, identify data quality issues, and prepare the data for future machine learning tasks.

## Dataset

The dataset contains information about students, including demographic details, test preparation status, and math, reading, and writing scores.

**Source:** [Students Performance in Exams — Kaggle](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Preprocessing Steps

1. **Data Loading and Inspection** — Loaded the CSV file and examined its structure, data types, and statistical summary.
2. **Column Name Standardization** — Converted column names into a consistent format.
3. **Missing Value Handling** — Checked missing values and handled them using median imputation for numerical columns and mode imputation for categorical columns.
4. **Duplicate Removal** — Identified and removed duplicate records.
5. **Outlier Detection** — Used the Interquartile Range (IQR) method to identify potential outliers in student scores.
6. **Manual One-Hot Encoding** — Converted categorical features into numerical columns using conditional statements.
7. **Feature Engineering** — Created an average score feature from math, reading, and writing scores.
8. **Feature Scaling** — Applied StandardScaler to standardize numerical score features.
9. **Exporting Cleaned Data** — Saved the processed dataset as a CSV file.

## Project Structure

```text
student-performance-data-preprocessing/
├── StudentsPerformance.csv
├── preprocessing.ipynb
├── cleaned_student_dataset.csv
└── README.md
```

*Note: Add the dataset and cleaned output only if you intend to include them in the repository. The notebook should contain the preprocessing code and explanations.*

## Learning Outcomes

- Practiced data inspection and exploratory data analysis.
- Learned to identify and handle missing values and duplicate records.
- Applied the IQR method for outlier detection.
- Implemented manual One-Hot Encoding.
- Practiced feature engineering and standardization.
- Prepared a dataset for potential downstream machine learning tasks.

## How to Run

1. Clone or download this repository.
2. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib scikit-learn jupyter
   ```

3. Open `preprocessing.ipynb` in Jupyter Notebook.
4. Place the original dataset in the appropriate folder.
5. Run the notebook cells in order.

## Notes

The original dataset may not contain missing values or duplicate records. If synthetic missing values are introduced for practice, document that clearly in the notebook.

Outlier detection does not automatically mean outlier removal. Detected values should be reviewed before making changes.

## Author

**Mishal Aqeel**

AI Student | Interested in Machine Learning and Data Science
