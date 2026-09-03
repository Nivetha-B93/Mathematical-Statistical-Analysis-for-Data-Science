# Mathematical & Statistical Analysis for Data Science

## 📌 Project Overview

This project demonstrates the practical application of **mathematical and statistical concepts used in Data Science** using Python.

The project focuses on understanding how mathematical foundations such as **linear algebra** and statistical concepts such as **probability, probability distributions, and descriptive statistics** can be implemented programmatically using Python libraries.

The analysis was performed using **NumPy, Pandas, SciPy, and Python's Statistics library**.

---

## 🎯 Objectives

The main objectives of this project are to:

* Apply linear algebra concepts using NumPy
* Perform vector and matrix operations
* Calculate determinants and matrix inverses
* Compute eigenvalues and eigenvectors
* Understand probability using customer purchase data
* Apply conditional probability
* Apply Bayes' theorem
* Simulate binomial, normal, and uniform distributions
* Calculate descriptive statistics
* Measure skewness and kurtosis
* Interpret the shape and distribution of data

---

## 🛠️ Technologies & Libraries

* **Python**
* **NumPy** – Numerical and linear algebra operations
* **Pandas** – Data manipulation and statistical analysis
* **SciPy** – Probability distributions and statistical calculations
* **Statistics** – Mean, median, and mode calculations
* **Matplotlib** – Data visualization where applicable
* **Jupyter Notebook** – Development and documentation environment

---

# 📂 Project Structure

```text
Mathematical-Statistical-Analysis-for-Data-Science/
│
├── Mathematical_&_Statistical_Analysis_for_Data_Science.ipynb
├── README.md
└── requirements.txt
```

---

# 📊 Project Tasks

## 1. Linear Algebra Implementation

A numerical dataset containing vectors and matrices was used to demonstrate fundamental linear algebra operations.

### Vector Operations

The project performs:

* Vector addition
* Vector subtraction
* Dot product

Example vectors:

```python
vector_a = np.array([2, 4, 6])
vector_b = np.array([1, 3, 5])
```

### Matrix Operations

The following matrix operations were performed:

* Matrix addition
* Matrix multiplication
* Determinant calculation
* Matrix inverse
* Eigenvalues
* Eigenvectors

Example matrix:

```python
matrix_a = np.array([
    [2, 1, 3],
    [1, 0, 2],
    [4, 1, 1]
])
```

The determinant of `matrix_a` was calculated before finding its inverse.

---

# 🎲 2. Probability Analysis

A customer purchase dataset was used to demonstrate probability concepts.

The project includes:

### Probability of Successful Sales

Customer segments and their purchase probabilities were used to calculate the overall probability of a successful sale.

The calculated probability of successful sales was:

**69.5%**

### Conditional Probability

The probability of a purchase given a particular customer segment was demonstrated.

For example:

```text
P(Purchase | Premium) = 0.80
P(Purchase | Regular) = 0.50
```

This demonstrates how customer segmentation can influence purchase probability.

---

# 🔄 3. Bayes' Theorem

Bayes' theorem was applied to determine the probability that a customer is Premium given that they made a purchase.

Given:

```text
P(A) = 0.40
P(B) = 0.62
P(B|A) = 0.80
```

The formula used was:

```text
P(A|B) = [P(B|A) × P(A)] / P(B)
```

The resulting probability was approximately:

**51.61%**

### Interpretation

Given that a customer made a purchase, there is approximately a **51.61% probability that the customer is a Premium customer**.

---

# 📈 4. Probability Distributions

The project demonstrates multiple probability distributions.

## Binomial Distribution

Parameters:

```python
n_trials = 20
success_prob = 0.65
```

A binomial distribution was simulated for **20 trials** with a **65% probability of success**.

The simulation demonstrates how the number of successful outcomes can vary across repeated experiments.

---

## Normal Distribution

A normal distribution was generated using:

```python
normal_mean = 50
normal_std = 10
```

This represents a distribution with:

* Mean = 50
* Standard deviation = 10

---

## Uniform Distribution

A uniform distribution was generated between:

```python
uniform_low = 0
uniform_high = 1
```

This demonstrates a distribution where values within the specified range have equal likelihood.

---

# 📐 5. Descriptive Statistics

A sales dataset was analyzed to understand its central tendency and variability.

```python
sales_data = [
    120, 135, 150, 145, 160, 155, 170, 165, 180, 175,
    190, 200, 210, 195, 185, 175, 165, 155, 145, 135
]
```

### Central Tendency

The following measures were calculated:

| Statistic |                  Result |
| --------- | ----------------------: |
| Mean      |                     165 |
| Median    |                     165 |
| Mode      | 135, 145, 155, 165, 175 |

The dataset is **multimodal**, as several values occur twice.

---

## 📏 Measures of Variability

The project calculates:

* Range
* Variance
* Standard deviation

Results:

| Measure            | Result |
| ------------------ | -----: |
| Range              |     90 |
| Variance           | 541.25 |
| Standard Deviation |  23.26 |

These measures help understand the spread and variability of sales values.

---

# 📉 6. Skewness & Kurtosis

Skewness and kurtosis were calculated to understand the distribution of the sales data.

### Skewness

The skewness is approximately:

**0**

Therefore, the dataset is approximately **symmetric**.

The mean and median are also both **165**, supporting this interpretation.

### Interpretation

```text
Skewness > 0  → Positively skewed
Skewness < 0  → Negatively skewed
Skewness ≈ 0  → Approximately symmetric
```

### Kurtosis

The kurtosis is approximately **-0.96**, indicating a relatively flatter distribution compared with a normal distribution.

---

# 💡 Key Learnings

Through this project, I strengthened my understanding of:

* Linear algebra fundamentals
* Vector and matrix manipulation
* Matrix inverse and determinant
* Eigenvalues and eigenvectors
* Probability fundamentals
* Conditional probability
* Bayes' theorem
* Binomial distribution
* Normal distribution
* Uniform distribution
* Descriptive statistics
* Measures of central tendency
* Measures of dispersion
* Skewness and kurtosis
* Statistical interpretation

---

# 🚀 Skills Demonstrated

### Programming

* Python
* NumPy
* Pandas
* SciPy

### Mathematics

* Linear Algebra
* Vectors
* Matrices
* Determinants
* Matrix Inverse
* Eigenvalues & Eigenvectors

### Statistics

* Mean
* Median
* Mode
* Range
* Variance
* Standard Deviation
* Skewness
* Kurtosis

### Probability

* Basic Probability
* Conditional Probability
* Bayes' Theorem
* Binomial Distribution
* Normal Distribution
* Uniform Distribution

---

# 👩‍💻 About Me

I am an **aspiring Data Scientist** with a strong interest in data analysis, statistics, Python, and data-driven problem solving.

I am currently building my skills in **Python, SQL, Excel, Power BI, Tableau, Statistics, and Data Science** through hands-on projects and practical exercises.

This project represents my effort to strengthen the mathematical and statistical foundation required for a career in Data Science.

---

# 📁 Project Files

* `Mathematical_&_Statistical_Analysis_for_Data_Science.ipynb` – Complete Jupyter Notebook containing the implementation and analysis.

---

# 🔮 Future Improvements

Possible extensions to this project include:

* Add visualizations for all probability distributions
* Compare theoretical and simulated distributions
* Perform hypothesis testing
* Calculate confidence intervals
* Add correlation and covariance analysis
* Implement statistical tests using SciPy
* Build an interactive dashboard based on the statistical analysis

---

## ⭐ Conclusion

This project provides a practical introduction to the **mathematical and statistical foundations of Data Science**.

By implementing these concepts using Python, I gained hands-on experience in converting mathematical formulas and statistical concepts into practical computational solutions.
