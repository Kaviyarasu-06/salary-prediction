# Linear Regression — Study Hours → Exam Score

This repository contains a simple end-to-end **Linear Regression** example that models **Exam Score** as a function of **Study Hours**. The main notebook file is `linear.ipynb`.

---

## Project overview

* **Goal:** Fit a simple linear regression model to predict exam scores from the number of study hours. Report the model's **slope**, **intercept**, **R²**, and make predictions for new inputs.
* **Included:** `linear.ipynb` — a documented Jupyter notebook with data loading, EDA, model fitting, evaluation, and visualization.

---

## Files

* `linear.ipynb` — Main notebook.
* `README.md` — This file.

> If you add data files, place them in a `data/` folder and update the notebook to point to `data/<filename>.csv`.

---

## Requirements

Recommended Python environment (tested on Python 3.8+):

```bash
pip install -r requirements.txt
# or install individually
pip install numpy pandas matplotlib scikit-learn jupyter
```

You can create a lightweight `requirements.txt` with:

```
numpy
pandas
matplotlib
scikit-learn
jupyter
seaborn
```

---

## How to run

1. Start Jupyter Notebook / Lab:

```bash
jupyter notebook
# or jupyter lab
```

2. Open `linear.ipynb` in the browser.
3. Run the cells in order. The notebook is structured so you can re-run every cell from top to bottom.

---

## Notebook structure (what to expect)

1. **Data loading** — loads the dataset (or creates a sample dataset) and displays the first rows.
2. **Exploratory Data Analysis (EDA)** — scatter plot of `Hours` vs `Score`, summary statistics, and checks for missing values.
3. **Model training** — fits `sklearn.linear_model.LinearRegression`, prints the **slope** (coefficient) and **intercept**.
4. **Evaluation** — computes **R²**, MAE, MSE, RMSE and interprets model goodness-of-fit. Optionally shows residual plots.
5. **Prediction** — example: predict score for `Hours = 9` (or any other value).
6. **Visualization** — plot of data points and regression line.

---

## Example outputs to look for

* **Slope (coefficient):** change in predicted score per additional hour of study.
* **Intercept:** predicted score at 0 hours of study.
* **R² score:** proportion of variance explained by the model.
* **Predicted score for hours = 9:** an example single prediction shown in the notebook.

---

## Tips & next steps

* Try **train/test split** to measure generalization: `train_test_split` from scikit-learn.
* Add **cross-validation** or **confidence intervals** for coefficients.
* Extend to **multiple linear regression** by adding more predictors (attendance, prior GPA, sleep hours).
* Check assumptions: linearity, homoscedasticity, normality of residuals, and independence.

---

## License

This project is released under the MIT License. Feel free to reuse and adapt.

---

## Contact

If you want changes to this README or additional files (requirements.txt, a sample `data/` CSV, or a cleaned notebook), tell me what you prefer and I’ll add them.

---

*Generated for `linear.ipynb` — quick linear regression demo.*
