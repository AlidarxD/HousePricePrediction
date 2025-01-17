# 🏠 House Price Prediction

Welcome to the **House Price Prediction** project! This repository uses machine learning techniques to predict house prices based on key features such as size, number of bedrooms, bathrooms, and additional amenities. 🏡✨

---

## 🌟 Project Highlights

- **Objective**: Build a predictive model for house prices using linear regression.
- **Dataset**: A rich dataset of 545 entries with 13 features, including both numerical and categorical variables.
- **Key Techniques**:
  - Data cleaning and transformation.
  - Exploratory data analysis (EDA) with visualizations.
  - Feature scaling and encoding.
  - Model evaluation with cross-validation.

---

## 📂 Dataset Description

The dataset contains **545 rows** and **13 features**. Below are the key attributes:

| Feature               | Description                                              |
|-----------------------|----------------------------------------------------------|
| `price`               | Target variable (house price in currency units).         |
| `area`                | Size of the house (square feet).                         |
| `bedrooms`            | Number of bedrooms.                                      |
| `bathrooms`           | Number of bathrooms.                                     |
| `stories`             | Number of floors.                                        |
| `mainroad`            | Proximity to the main road (`yes`/`no`).                 |
| `guestroom`           | Presence of a guestroom (`yes`/`no`).                    |
| `basement`            | Presence of a basement (`yes`/`no`).                     |
| `hotwaterheating`     | Availability of hot water heating (`yes`/`no`).          |
| `airconditioning`     | Availability of air conditioning (`yes`/`no`).           |
| `parking`             | Number of parking spaces.                                |
| `prefarea`            | Located in a preferred area (`yes`/`no`).                |
| `furnishingstatus`    | Furnishing type: `furnished`, `semi-furnished`, `unfurnished`. |

---

## 🔍 Exploratory Data Analysis

1. **Data Distribution**:
   - Histograms reveal the distribution of features like `price`, `area`, and `bedrooms`.

2. **Correlation Heatmap**:
   - Insights into feature relationships, showing strong positive correlations of `price` with `area` and `stories`.

3. **Scatter Plot**:
   - Visualized `area` vs. `price`, enhanced with `bedrooms` as a color gradient for better insights.

   Example:
   ![Scatter Plot](https://via.placeholder.com/800x400?text=Scatter+Plot+Preview)  
   *(Replace this link with an actual plot image)*

---

## 🧠 Machine Learning Model

- **Algorithm**: Linear Regression.
- **Preprocessing**:
  - Logarithmic transformation of skewed features (`bedrooms`, `bathrooms`, `stories`, `parking`).
  - Categorical encoding for binary and multi-class variables.
  - Feature scaling with `StandardScaler`.
- **Cross-validation**:
  - Achieved an average \( R^2 \) score of **0.6519**, indicating moderate predictive capability.

---

## 📊 Results and Insights

- **Key Drivers of House Price**:
  - **Area**: Larger houses correlate with higher prices.
  - **Stories**: More stories often increase value.
  - **Air Conditioning**: A significant differentiator for pricing.

- **Performance**:
  - The model performs well with scaled features, but further optimization (e.g., non-linear models) could enhance accuracy.

---

## 🚀 How to Run the Project

### Prerequisites
1. Install Python 3.8+.
2. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/AlidarxD/HousePricePrediction.git
   ```
2. Navigate to the folder:
   ```bash
   cd HousePricePrediction
   ```
3. Place the dataset in the folder `archive (7)` as `Housing.csv`.
4. Open the Jupyter Notebook (`house.ipynb`) and run all cells.

---

## 🛠️ Technologies Used

- **Python**: Core programming language.
- **Pandas**: Data manipulation and analysis.
- **NumPy**: Numerical operations.
- **Matplotlib & Seaborn**: Data visualization.
- **Scikit-learn**: Machine learning library.

---

## 📝 Future Enhancements

- Implement advanced models like Random Forest or Gradient Boosting.
- Optimize feature selection using techniques like Recursive Feature Elimination (RFE).
- Explore hyperparameter tuning for better model performance.

---

## 💡 Author

**Alidar**  
GitHub: [AlidarxD](https://github.com/AlidarxD)  
