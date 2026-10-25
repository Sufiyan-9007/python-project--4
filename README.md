# Data Analyzer & Transformer Program

A modern, interactive, menu-driven Python application designed for 1D array data manipulation, mathematical computation, and statistical analysis.

---

## 🚀 Key Features

* **Interactive CLI Menu:** User-friendly command-line interface for smooth navigation.
* **Data Ingestion:** Seamless space-separated input handling for 1D numerical datasets.
* **Smart Summaries:** Quick extraction of basic properties like min, max, sum, and averages.
* **Statistical Insights:** On-the-fly calculations for Mean, Median, and Standard Deviation.
* **Advanced Transformations:** Built-in lambdas for custom threshold filtering and full sorting arrays.
* **Bonus Math Utilities:** Integrated iterative factorial processor.

---

## 📊 Terminal Output Preview

Here is how the application executes in the command line interface:

### 📥 1. Inputting Dataset (Option 1 & 2)
```text
Welcome to the Data Analyzer And Transformer Program

Select an option:
1. Input Data
2. Display Data Summary
3. Calculate Factorial
4. Filter Data by Threshold
5. Sort Data
6. Display Dataset Statistics
7. Exit Program

Please enter your choice number: 1
Enter data for a 1D array (separated by spaces):
10 20 30 40 50
Data has been stored successfully!

Please enter your choice number: 2

Data Summary:
- Total elements: 5
- Minimum value: 10
- Maximum value: 50
- Sum of all values: 150
- Average value: 30.00
```

### 📈 2. Advanced Statistics & Filtering (Option 6 & 4)
```text
Please enter your choice number: 6

Dataset Statistics:
- Mean: 30.00
- Median: 30.00
- Standard Deviation: 14.14

Please enter your choice number: 4
Enter the threshold value: 25
Elements greater than 25: [30, 40, 50]
```

---

## 🛠️ Menu Operations Reference

| Option | Operation | Description |
| :--- | :--- | :--- |
| **1** | **Input Data** | Ingest space-separated integers into the active dataset |
| **2** | **Display Data Summary** | View count, minimum, maximum, sum, and average values |
| **3** | **Calculate Factorial** | Compute the mathematical factorial for any specific integer |
| **4** | **Filter Data** | Extract values strictly higher than a custom user threshold |
| **5** | **Sort Data** | Arrange the active dataset in Ascending or Descending order |
| **6** | **Dataset Statistics** | Calculate high-level statistical values (Mean, Median, Std Dev) |
| **7** | **Exit Program** | Terminate execution and clear application memory safely |

---

## 🔧 Prerequisites & Setup

### Requirements
* Python 3.6 or higher installed on your local environment.

### Execution
1. Open your terminal or command prompt inside the project folder.
2. Launch the script using:
   ```bash
   python "Python Project.py"
   ```
