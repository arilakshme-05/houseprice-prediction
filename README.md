# House Price Prediction

A Machine Learning project that predicts house prices using Linear Regression on the Boston Housing dataset.

---

##  Features

* **Data Selection:** Analyzes subset samples for targeted modeling.
* **Model Training:** Applies Simple Linear Regression for price estimation.
* **Performance Evaluation:** Evaluates model performance using Mean Squared Error (MSE) and R^2 Score.
* **Data Visualization:** Generates scatter plots comparing Actual vs. Predicted house prices.

---

##  Technologies Used

* **Language:** Python 3
* **Environment:** Google Colab / Jupyter Notebook
* **Libraries:**
  * `pandas` – Data manipulation and structured data analysis
  * `scikit-learn` – Model training, train-test splitting, and evaluation metrics
  * `matplotlib` & `seaborn` – Visualizing regression trend lines and scatter plots

---

##  Dataset

* **Dataset:** Boston Housing Dataset
* **Description:** Contains structural, demographic, and environmental attributes of housing in the Boston area.

---

##  Project Workflow

1. **Load Dataset:** Import the Boston Housing dataset.
2. **Data Selection:** Select the target dataset sample (e.g., first 100 entries).
3. **Train-Test Split:** Partition features and targets into training and testing sets.
4. **Model Training:** Fit a Linear Regression model on the training data.
5. **Prediction:** Run price inference on unseen test samples.
6. **Evaluation:** Calculate performance metrics using MSE and $R^2$ score.
7. **Visualization:** Plot a scatter diagram comparing actual vs. predicted values.

---

##  Output & Results

The application outputs model error metrics (MSE and R^2) alongside a scatter plot contrasting actual values against predicted house prices to evaluate linear model fit.

---

##  How to Run

1. Clone the repository:
   git clone [https://github.com/arilakshme-05/houseprice-prediction.git](https://github.com/arilakshme-05/houseprice-prediction.git)
   cd houseprice-prediction

2.Install dependencies:
pip install pandas scikit-learn matplotlib seaborn

3.Run Environment:
Open and execute the notebook in Google Colab or Jupyter Notebook.
