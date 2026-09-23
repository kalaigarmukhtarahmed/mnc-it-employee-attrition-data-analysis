# Employee Attrition Data Analysis

A Python-based Data Science project for analyzing an employee attrition dataset using data cleaning, sampling, transformation, preprocessing, and statistical analysis techniques.

## Project Overview

This project demonstrates the basic Data Science workflow using an employee attrition dataset from an MNC/IT employee context.

The analysis covers:

* Dataset loading
* Missing/null value identification
* Sampling
* Data cleaning
* Missing value handling
* Data transformation
* Categorical data encoding
* Numerical feature preprocessing
* Standardization
* Mean, median, and mode
* Variance
* Standard deviation
* Coefficient of Variation (CV)

## Dataset

The project uses:

`MNC_IT_employee_attrition_sample.csv`

The dataset contains employee-related information such as:

* Employee ID
* Company
* Department
* Job Role
* Location
* Gender
* Education
* Employment Type
* Work Mode
* Job Level
* Monthly Salary
* Salary Growth Potential
* Attrition
* and other employee attributes

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy
* Scikit-learn
* Jupyter Notebook

## Data Science Workflow

The notebook follows this sequence:

### 1. Load Dataset

The employee attrition dataset is loaded using Pandas.

### 2. Find Missing Values

Null/missing values are identified using Pandas.

### 3. Sampling

A sample of the dataset is selected using random sampling while keeping the original dataset unchanged.

### 4. Data Cleaning

The dataset is cleaned by:

* Removing duplicate records
* Removing duplicate Employee IDs
* Cleaning string values
* Handling missing categorical values
* Handling missing numerical values

### 5. Missing Value Handling

Categorical missing values are handled using an appropriate placeholder, while numerical missing values are filled using the median.

### 6. Data Transformation

Categorical and other required fields are transformed into numerical representations.

Examples include:

* Job Level encoding
* Salary Growth Potential encoding
* Attrition binary encoding
* One-hot encoding for nominal categorical features

### 7. Data Preprocessing

Numerical features are standardized using `StandardScaler`.

### 8. Statistical Analysis

The project calculates:

* Mean
* Median
* Mode
* Variance
* Standard Deviation
* Coefficient of Variation

## Statistical Analysis

The analysis focuses on the `Monthly_Salary_INR` feature.

The following statistical measures are calculated:

**Mean**

Average monthly salary of employees.

**Median**

Middle value of the monthly salary distribution.

**Mode**

Most frequently occurring monthly salary.

**Variance**

Measures the spread of monthly salary values around the mean.

**Standard Deviation**

Measures the amount of variation in monthly salary values.

**Coefficient of Variation**

CV is calculated as:

```text
CV = (Standard Deviation / Mean) × 100
```

## Project Structure

```text
employee-attrition-data-analysis/
│
├── data/
│   └── MNC_IT_employee_attrition_sample.csv
│
├── notebooks/
│   └── Employee_Attrition_Data_Analysis.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore
```

## How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/employee-attrition-data-analysis.git
```

### 2. Open the project

```bash
cd employee-attrition-data-analysis
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Open the notebook

Open:

```text
notebooks/Employee_Attrition_Data_Analysis.ipynb
```

Run the cells sequentially.

## Requirements

The project requires:

```text
numpy
pandas
matplotlib
seaborn
scipy
scikit-learn
jupyter
```

## Key Learning Outcomes

Through this project, the following Data Science concepts are demonstrated:

* Data loading
* Data inspection
* Missing value analysis
* Sampling
* Data cleaning
* Data transformation
* Categorical encoding
* Feature scaling
* Descriptive statistics
* Statistical variability
* Python data analysis using Pandas and NumPy

## Author

**Kalaigar Mukhtar Ahmed**

Computer Science and Engineering Student

## License

This project is created for educational and academic purposes.
