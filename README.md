# ⚙️ Functional Treat — Data Analyzer & Transformer

An interactive menu-driven Python project that demonstrates the power of functions — covering recursion, lambda expressions, filtering, sorting, and statistical analysis on user-provided datasets.

---

## 🚀 Features

| Feature | Description |
|---|---|
| Input Data | Accept a list of numbers from the user |
| Data Summary | Display count, min, max, sum and average |
| Calculate Factorial | Compute factorial using recursion |
| Filter by Threshold | Filter values greater than a given number using `lambda` |
| Sort Data | Sort in ascending or descending order |
| Dataset Statistics | Detailed statistical overview of the dataset |

---

## 🛠️ Tech Stack

- **Language:** Python 3.11
- **Concepts:** Functions (`def`), Recursion, Lambda, `filter()`, `sorted()`, `map()`, List Comprehension
- **Tool:** Jupyter Notebook

---

## 📁 Project Structure

```
python-functions/
│
├── Functional_Treat.ipynb   # Main Jupyter Notebook
└── README.md                # Project documentation
```

---

## ▶️ How to Run

1. Clone the repository
```bash
git clone https://github.com/ravindra-data/python-functions.git
```

2. Open the notebook
```bash
jupyter notebook Functional_Treat.ipynb
```

3. Run the cell and interact with the menu!

---

## 📸 Sample Output

```
Welcome to the Data Analyzer and Transformer Program!
--Main Menu--
1. Input Data          → Enter: 90 20 50 80

2. Display Data Summary
   - Total elements : 4
   - Minimum value  : 20
   - Maximum value  : 90
   - Sum            : 240
   - Average        : 60.0

3. Calculate Factorial → Input: 5 → Output: 120

4. Filter Threshold    → Greater than 30 → [90, 50, 80]

5. Sort Data           → Ascending → [20, 50, 80, 90]
```

---

## 💡 What I Learned

- Writing and organizing modular functions using `def`
- Implementing recursion for factorial calculation
- Using `lambda` with `filter()` for data filtering
- Applying `sorted()` with `reverse` parameter
- Computing basic statistics without external libraries

---
