# HR Analytics Using Python

A five-part data analysis project on Human Resources data. It covers employee performance, attrition, recruitment, salary and training, using Python in Jupyter Notebook.

## What this project answers

| Part | Topic | Main question |
|------|-------|---------------|
| 1 | Employee Performance and Productivity | Which departments and roles perform best? |
| 2 | Employee Attrition and Retention | Who leaves the company, and why? |
| 3 | Recruitment and Hiring Funnel | Where are candidates lost during hiring? |
| 4 | Salary Distribution and Compensation | How are salaries spread, and who earns more? |
| 5 | Training and Skill Development | Which training programs work best, and at what cost? |

## Highlights

- **Performance:** IT has the highest average performance score (76.88) and Customer Support the lowest (70.56). Completing more projects or working longer hours does not guarantee better performance.
- **Attrition:** 23% of employees left. Customer Support has the highest attrition (27.61%), and employees with a job satisfaction score of 1 leave far more often (46.30%).
- **Recruitment:** The biggest drop in the hiring funnel is between screening and interview.
- **Salary:** Technology pays the most on average and Administration the least. Higher experience and education go with higher pay.
- **Training:** Data Analytics gives the highest average score improvement (11.87) and Compliance Training the lowest (6.06).

## Workflow followed in every part

1. Load the data and understand its structure
2. Check quality: missing values, duplicates, invalid values
3. Clean and standardise (for example "H.R." and "Human Resources" become one department)
4. Calculate statistics and group-wise metrics
5. Visualise with bar charts, scatter plots, box plots and histograms
6. Interpret the results and give recommendations

## Tools

Python, Pandas, NumPy, Matplotlib, Jupyter Notebook

## Repository structure

```text
HR-Analytics-Using-Python/
├── notebooks/
│   ├── Assessment Task 1.ipynb
│   ├── Assessment Task 2.ipynb
│   ├── Assessment Task 3.ipynb
│   ├── ASSESSMENT TASK 4.ipynb
│   └── ASSESSMENT TASK 5.ipynb
├── LICENSE
└── README.md
```

## How to run

```bash
git clone https://github.com/connectvishalsagar-eng/HR-Analytics-Using-Python.git
cd HR-Analytics-Using-Python
pip install pandas numpy matplotlib jupyter
jupyter notebook
```

Open any notebook from the `notebooks` folder. Each notebook reads its own CSV file, so update the file path in the first cells to where your data is saved.

## Skills demonstrated

Data cleaning, data manipulation with Pandas, exploratory data analysis, descriptive statistics, data visualisation and writing clear interpretations.

## Author

**Vishal Sagar**, aspiring Data Analyst

## License

Released under the [MIT License](LICENSE).
