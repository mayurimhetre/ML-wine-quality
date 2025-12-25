## 🍷 Wine Quality Prediction (Machine Learning)

### 📖 About the Dataset
The **Wine Quality Dataset** contains physicochemical properties of red and white wine samples. Each sample is described by several numerical features such as acidity, sugar content, pH, alcohol level, and sulfur dioxide levels.

The quality of wine is rated on a scale from **0 to 10**, based on sensory evaluation by experts.

Common features include:
- Fixed acidity
- Volatile acidity
- Citric acid
- Residual sugar
- pH
- Alcohol
- Sulphates

---

### 🎯 Project Objective
The objective of this project is to **predict the quality of wine** using machine learning techniques based on its chemical properties.

### Implementation

#### 🌲 Random Forest
Random Forest is an ensemble learning algorithm that builds multiple decision trees using random subsets of data and features, then combines their predictions using majority voting or averaging. This approach reduces overfitting and improves model accuracy.

#### ⚡ XGBoost
XGBoost (Extreme Gradient Boosting) is a powerful boosting algorithm that builds trees sequentially, where each new tree corrects the errors made by previous ones. It uses gradient descent optimization and regularization to achieve high performance and efficiency.

---

### Results

Random Forest Classifier and XGboost classifier gives 70 % accuracy when 3 categories are formed.

- quality < 6 --- > "-1"
- quality == 6 ---> 0
- quality > 6 ---> "1"
