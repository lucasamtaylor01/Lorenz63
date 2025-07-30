# Lorenz63 🌀

## 📌 Overview

The Lorenz system is a simplified model for atmospheric convection introduced by Edward Lorenz in 1963. It consists of three ODEs:

$$dx/dt = \sigma(y − x)$$
$$dy/dt = x(\rho − z) − y$$
$$dz/dt = xy − \beta z$$


This project explores numerical solutions and the chaotic behavior of the Lorenz attractor.

## 🚀 Features

- RK4 integration of the Lorenz system
- 2D/3D trajectory plots
- Sensitivity to initial conditions
- Least squares analysis of divergence

## 📁 Project Structure

```
Lorenz63/
├── 01_report/ # PDF and LaTeX report (documentation and analysis)
├── 02_src/ # Source code (Jupyter notebooks, Python scripts)
├── LICENSE # MIT License
└── README.md # Project documentation
```

## 🛠 Dependencies

This project uses the following Python libraries:

- [`numpy`](https://numpy.org/) — numerical computing and array operations
- [`scipy`](https://scipy.org/) — solving ODEs and cubic spline interpolation
- [`matplotlib`](https://matplotlib.org/) — 2D and 3D plotting
- [`plotly`](https://plotly.com/python/) — interactive 3D visualizations
- [`pandas`](https://pandas.pydata.org/) — organizing and exporting data tables
- [`tabulate`](https://pypi.org/project/tabulate/) — rendering tables in notebook-friendly formats
- [`scikit-learn`](https://scikit-learn.org/) — performance metrics (MAE, MSE, explained variance)

## 👥 Authors

- **[Julio Cezar de Moura Lima](https://github.com/Juliocezar7253)**
- **[Lucas Amaral Taylor](https://github.com/lucasamtaylor01)**

