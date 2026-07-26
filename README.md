# 📊 Ridge Lasso Regression 🚀

---

## ✨ Project Goals

* 📈 Build and compare regression models for predicting `mpg` using the **Auto MPG** dataset
* 🧮 Understand the effect of car features on fuel efficiency through regression analysis
* 🎓 Practice data cleaning, feature inspection, and exploratory data analysis (EDA)
* 🔮 Explore the impact of **regularization** with `Ridge` and `Lasso` models
* 🛠️ Create a strong foundation for working with real-world tabular machine learning problems

---

## ⚡ Features

* ✅ Loads and analyzes the **Auto MPG** dataset from a CSV file
* ✅ Performs detailed dataset inspection:

  * 📍 Columns and data types
  * 📍 Missing values
  * 📍 Duplicate records
  * 📍 Correlation analysis
* ✅ Cleans the data by:

  * 📍 Removing the `car name` column
  * 📍 Replacing `?` values with `NaN`
  * 📍 Filling missing values using the mode
  * 📍 Converting `horsepower` to numeric format
* ✅ Creates visualizations for better understanding of the data:

  * 📍 Correlation heatmap
  * 📍 Origin distribution
  * 📍 MPG trend by model year
  * 📍 Cylinder distribution
  * 📍 Horsepower vs MPG scatter plot
* ✅ Trains and evaluates multiple regression models:

  * 📍 `LinearRegression`
  * 📍 `Ridge(alpha=0.2)`
  * 📍 `Lasso(alpha=0.2)`
* ✅ Displays model coefficients, intercepts, and train/test scores
* ✅ Tests different `alpha` values to compare regularization behavior

---

## 📦 Dataset

This project uses the classic **Auto MPG** dataset, which includes the following features:

* `mpg`
* `cylinders`
* `displacement`
* `horsepower`
* `weight`
* `acceleration`
* `model year`
* `origin`
* `car name`

The target variable is:

* **`mpg`** → Miles per gallon

---

## 🚀 How to Run

1. 🔗 Clone the repository:

   ```bash
   git clone https://github.com/Ramtin-Ebrahimi/Ridge_Lasso_Regression.git
   ```

2. 📦 Install the required libraries:

   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn jupyter
   ```

3. 🧠 Open Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. ▶️ Run the notebook:

   * `Ridge_Lasso_Regression(1).ipynb`

---

## 🛠️ Tech Stack

* 🐍 Python
* 📊 Pandas
* 🔢 NumPy
* 🎨 Matplotlib
* 🖼️ Seaborn
* 🤖 Scikit-learn

---

## 📌 Models Used

* ✅ Linear Regression
* ✅ Ridge Regression
* ✅ Lasso Regression

---

## 📈 Key Learning Outcomes

* 🧹 How preprocessing improves the quality of real-world data
* 📉 Why regularization matters in regression problems
* ⚖️ How Ridge and Lasso affect model coefficients
* 📊 How to compare models using train/test performance

---

## 👨‍💻 Author

**Ramtin Ebrahimi**

---

## ⭐ If you liked this project

Give the repository a **star** and explore the notebook to see the full workflow!
