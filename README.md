# Car Price Prediction

*This project aims to predict car prices based on various features such as car make, model, fuel type, engine specifications, and more.

*The workflow is implemented in a Jupyter Notebook: `car_price.ipynb`
*The dataset used is: `CarPrice_Assignment.csv`

## 📂 Project Structure

```
.
├── car_price.ipynb          # Main notebook with data analysis and model building
├── CarPrice_Assignment.csv  # Dataset containing car features and prices
└── README.md                # Project documentation
```

---

## 📊 Dataset

The dataset `CarPrice_Assignment.csv` contains details about cars and their prices.

Key columns include:

* `CarName` → Car model name
* `fueltype` → Type of fuel used (gas/diesel)
* `aspiration` → Standard/ turbo
* `doornumber` → Number of doors
* `carbody` → Body style (sedan, hatchback, etc.)
* `enginetype`, `cylindernumber`, `enginesize` → Engine specifications
* `horsepower`, `peakrpm`, `citympg`, `highwaympg` → Performance metrics
* `price` → Target variable (car price)

---

## 🔎 Workflow

1. **Exploratory Data Analysis (EDA)**

   * Data cleaning, handling categorical variables, feature distributions
   * Correlation analysis

2. **Feature Engineering**

   * Encoding categorical variables
   * Feature selection

3. **Model Building**

   * Linear Regression / Multiple Regression
   * Train-test split
   * Model evaluation using R², Adjusted R², RMSE

4. **Results & Insights**

   * Key features influencing car price
   * Model performance metrics

---

## ⚙️ Requirements

Install dependencies with:

```bash
pip install -r requirements.txt
```

Typical requirements:

* Python 3.8+
* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn
* jupyter

---

## 🚀 Usage

1. Clone this repository:

   ```bash
   git clone https://github.com/ItsFoD/car-price-prediction.git
   cd car-price-prediction
   ```

2. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

3. Open `car_price.ipynb` and run the cells step by step.

---

## 📈 Example Output

* Correlation heatmaps
* Regression model summary
* Predicted vs Actual prices plot

---


