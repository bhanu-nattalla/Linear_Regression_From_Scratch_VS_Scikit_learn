# Linear Regression from Scratch vs Scikit-learn

This project implements **Linear Regression** using **Gradient Descent** from scratch in Python and compares its performance with the built-in `LinearRegression` model from **scikit-learn**.

## 📌 Features
- Custom Linear Regression implementation using NumPy
- Comparison with Scikit-learn's implementation
- Evaluation using **Mean Squared Error (MSE)**

## 🚀 Installation

Clone the repository and install dependencies:

```bash
pip install -r requirements.txt
```

## 📂 Requirements
- numpy  
- scikit-learn  

## 🧑‍💻 Usage

Run the script:

```bash
python main.py
```

You will see output like:

```
Custom Model Mean Squared Error: 0.0803
Sklearn Model Mean Squared Error: 0.0797
```

## ✅ Comparison

- **Custom Model**: Uses manual gradient descent with adjustable learning rate and iterations.  
- **Scikit-learn Model**: Uses closed-form solution (Normal Equation).  

Both should perform similarly on this dataset, with minor differences due to noise and optimization steps.

---

✨ Built for learning purposes to understand the inner workings of Linear Regression.
"# linear-regression-scratch-vs-sklearn" 