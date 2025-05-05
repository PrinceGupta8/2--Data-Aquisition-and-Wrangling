# Data Acquisition and Wrangling Project

This project focuses on **data acquisition and wrangling** tasks for multiple datasets. It involves merging, cleaning, and preparing data for further analysis or modeling. The project is implemented in a Jupyter Notebook and follows a structured approach to handle datasets effectively.

---

## 📋 Project Overview

The project is divided into two main tasks:

1. **Task 1: Data Acquisition and Wrangling on Dataset 1 and Dataset 2**
   - Merge datasets.
   - Identify unique values.
   - Drop unnecessary columns.
   - Check dataset dimensions and data types.
   - Treat missing values.
   - Validate data correctness.

2. **Task 2: Data Acquisition and Wrangling on Dataset 3**
   - Concatenate the combined data from Task 1 with Dataset 3.
   - Handle missing values and outliers.
   - Analyze skewness and correlation of the data.

---

## 🛠️ Steps Performed

### Task 1: Data Acquisition and Wrangling on Dataset 1 and Dataset 2
1. **Import Libraries**:
   - `pandas` and `numpy` are used for data manipulation and analysis.

2. **Load Datasets**:
   - Dataset 1: `dataset_1.csv`
   - Dataset 2: `dataset_2.csv`

3. **Merge Datasets**:
   - Inner join on the `instant` column.

4. **Data Cleaning**:
   - Drop unnecessary columns like `instant`, `season`, `yr`, `mnth`, and `Unnamed: 0`.
   - Treat missing values by filling them with the mean.

5. **Data Validation**:
   - Check for duplicates.
   - Convert date columns to datetime format.

6. **Summary Statistics**:
   - Generate descriptive statistics for the combined data.

---

### Task 2: Data Acquisition and Wrangling on Dataset 3
1. **Load Dataset 3**:
   - Dataset 3: `dataset_3.csv`

2. **Concatenate Datasets**:
   - Combine the data from Task 1 with Dataset 3 using an inner join.

3. **Data Cleaning**:
   - Drop unnecessary columns like `instant`, `season`, `yr`, and `mnth`.
   - Treat missing values by filling them with the mean.

4. **Data Analysis**:
   - Check skewness and correlation of the data.

---

## 📂 Project Structure
.
├── datasets/
│   ├── dataset_1.csv
│   ├── dataset_2.csv
│   ├── dataset_3.csv
├── Project.ipynb
└── README.md


---

## 🚀 How to Run the Project

1. Clone the repository or download the project files.
2. Install the required Python libraries:
   ```bash
   pip install pandas numpy

3. Open the `Project.ipynb` file in Jupyter Notebook or any compatible IDE.
4. Run the cells sequentially to execute the project.

---

## 📊 Key Insights

- The merged dataset provides a comprehensive view of the data from multiple sources.
- Missing values were handled effectively to ensure data consistency.
- Correlation and skewness analysis help in understanding relationships and data distribution.

---

## 🛠️ Tools and Libraries Used

- **Python**: Programming language.
- **pandas**: For data manipulation and analysis.
- **numpy**: For numerical computations.

---

## 📈 Future Work

- Perform exploratory data analysis (EDA) on the cleaned dataset.
- Build predictive models using the prepared data.
- Visualize key insights using libraries like `matplotlib` or `seaborn`.

---

## 🤝 Contributing

Contributions are welcome! Feel free to submit a pull request or open an issue for suggestions.
