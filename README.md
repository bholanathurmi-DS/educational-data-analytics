# Standard Educational Data Analytics: Teacher Workforce & Student Enrolment

## Project Overview

This project analyzes school-level teacher workforce and student enrolment data using Python, Pandas, Matplotlib and Seaborn.

The analysis focuses on:

- School category-wise analysis
- School-wise teacher counts
- School-wise teacher names
- Student enrolment by class
- Teacher workforce distribution
- Student–Teacher Ratio
- School-level education indicators
- Identification of potential staffing and enrolment needs

## Dataset

The project uses two datasets:

1. `all_teachers_2026.csv`
   - Contains teacher-level information for schools.

2. `enrolment_2026.csv`
   - Contains class-wise student enrolment information.

## Key Analysis

### 1. School Category Analysis

Schools are grouped into categories such as:

- Primary
- Upper Primary
- High
- Higher Secondary

The analysis provides school counts, enrolment, teacher counts and student–teacher indicators by category.

### 2. School-wise Teacher Directory

The project creates a school-level teacher directory containing:

- School name
- School code
- School category
- Teacher count
- Teacher names
- Student enrolment
- Student–Teacher Ratio

### 3. Educational Planning

The analysis can be used to identify schools that may require further attention based on:

- High student enrolment
- Low teacher availability
- High Student–Teacher Ratio
- School category
- Teacher workforce distribution

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Structure

```text
GITHUB_Project1/
│
├── data/
│   ├── all_teachers_2026.csv
│   └── enrolment_2026.csv
│
├── notebooks/
│   └── 01_school_data_analytics.ipynb
│
├── outputs/
│   ├── school_teacher_enrolment_summary.csv
│   ├── school_category_summary.csv
│   └── school_teacher_directory.csv
│
└── README.md
