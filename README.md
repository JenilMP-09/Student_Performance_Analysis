# Student Performance Analysis

## Introduction
This project performs exploratory data analysis (EDA) on the **Student Performance Dataset** using Python.  
The notebook analyzes student academic performance, study habits, demographics, and other factors that may influence final grades.

The analysis is implemented in the Jupyter Notebook:

- `student_analysis.ipynb`

and uses the dataset:

- `student-mat.csv`

---

## Project Structure

```bash
.
├── student_analysis.ipynb   # Main notebook containing analysis and visualizations
├── student-mat.csv          # Dataset used for analysis
└── README.md                # Project documentation
```

---

## Dataset Information

- **Dataset Name:** Student Performance Dataset
- **Rows:** 395
- **Columns:** 33

### Features Included
school, sex, age, address, famsize, Pstatus, Medu, Fedu, Mjob, Fjob, reason, guardian, traveltime, studytime, failures, schoolsup, famsup, paid, activities, nursery, higher, internet, romantic, famrel, freetime, goout, Dalc, Walc, health, absences, G1, G2, G3

The dataset contains information related to:
- Student demographics
- Family background
- Study time
- Alcohol consumption
- Attendance
- Academic performance

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn

---

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/JenilMP-09/Student_Performance_Analysis
cd <repository-folder>
```

### 2. Install Dependencies

```bash
pip install pandas matplotlib seaborn notebook
```

### 3. Launch Jupyter Notebook

```bash
jupyter notebook
```

Then open:

```bash
student_analysis.ipynb
```

---

## Analysis Performed

The notebook includes the following steps:

### 1. Load Dataset
- Read the CSV dataset using Pandas
- Display the dataset contents
- Preview first rows of the dataset

### 2. Data Exploration & Cleaning
- Inspect dataset information
- Check for missing values
- Remove duplicate records
- Verify dataset shape and data types

### 3. Data Analysis Questions
The project answers questions such as:

- What is the average final grade (`G3`)?
- How many students scored above 15?
- Is study time correlated with performance?
- Which gender performs better on average?

### 4. Data Visualization
The notebook includes visualizations such as:

- Histogram of grades
- Scatterplot of study time vs grades
- Bar chart comparing male vs female average grades

---

## Key Insights

- The dataset does not contain missing values.
- The dataset does not contain duplicate values.
- Study time shows a relationship with student performance.
- Male students performed slightly better on average in this analysis.

---

## Example Usage

Run all notebook cells sequentially to reproduce the analysis and charts.

Example:

```python
import pandas as pd

df = pd.read_csv("student-mat.csv", sep=";")

print(df.head())
```

---

## Output

The notebook generates:
- Summary statistics
- Cleaned dataset insights
- Charts and visualizations
- Correlation observations

---

## Future Improvements

Possible enhancements for this project:
- Add machine learning models for grade prediction
- Perform advanced statistical analysis
- Create interactive dashboards
- Compare multiple student datasets

---

## License

This project is open-source and available under the MIT License.

---

## Author

Created for educational and data analysis practice purposes.
