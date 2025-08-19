# Python Fundamentals Capstone Project

### Project Overview
This project is a capstone for the Python Fundamentals course by SkilloVilla. It focuses on creating a data wrangling and analytics pipeline to clean and integrate three separate datasets: Project, Employee, and Seniority. The goal was to transform raw, fragmented data (containing missing values and inconsistencies) into a clean, analysis-ready format.

---

### Tasks & Business Rules
This project addresses a series of data processing and business logic challenges:
- **Data Loading:** Created three separate DataFrames from raw data and saved them as `.csv` files for reproducibility.
- **Data Cleaning & Integration:**
    - Imputed missing project costs using a rolling average method.
    - Split the 'name' column into 'First Name' and 'Last Name'.
    - Merged all three DataFrames into a single, consolidated dataset.
- **Business Rule Implementation:**
    - Applied a 5% bonus to employees who finished their projects.
    - Adjusted employee designation levels based on project performance (demoting for failed projects and promoting for employees over 29 years old).
- **Data Transformation & Aggregation:**
    - Added "Mr." and "Mrs." prefixes to names and removed the gender column.
    - Calculated the total project cost for each employee.
    - Filtered and displayed employee details based on specific city patterns.

---

### Project Impact
* **Data Completeness:** Improved data completeness from approximately **85.7% to 100%** after imputing missing values[cite: 5].
* **Automated Insights:** The pipeline automates the application of complex business rules, such as bonus calculations and designation adjustments.
* **Analysis-Ready Data:** Delivered a comprehensive, fully documented Jupyter Notebook (`.ipynb` file) that provides a single, reliable source for business analytics.

---

### Technologies Used
* **Python:** The core programming language for the project.
* **Pandas:** Used extensively for data manipulation, cleaning, and analysis.
* **NumPy:** Utilized for numerical operations and data processing.

---

### Files in this Repository
- `capstone_project.ipynb`: The main Jupyter Notebook containing all code and outputs.
- `project.csv`: The Project DataFrame saved as a CSV file.
- `employee.csv`: The Employee DataFrame saved as a CSV file.
- `seniority_level.csv`: The Seniority Level DataFrame saved as a CSV file.
