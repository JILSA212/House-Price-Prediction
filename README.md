# House-Price-Prediction
🏡 House Price Prediction

This project builds a machine learning model to predict house prices using a dataset available on Kaggle. The model is developed using Python and popular libraries such as pandas, scikit-learn, and matplotlib.

📊 Dataset
The dataset used for this project is from Kaggle: <br>
https://www.kaggle.com/datasets/amitabhajoy/bengaluru-house-price-data <br>
It includes features such as area type, availability, location, size, society, etc, to predict the final sale price of a house.

📁 Project Structure
bash
Copy
Edit
├── HousePricePrediction.ipynb  # Jupyter notebook with full analysis and modeling
├── README.md                   # Project documentation


## 🔧 Features and Workflow

The notebook walks through the following stages:

1. **Exploratory Data Analysis (EDA)**  
   - Handling missing values  
   - Visualizations to understand data distributions and correlations  

2. **Data Preprocessing**  
   - Encoding categorical variables  
   - Feature selection and scaling  

3. **Modeling**  
   - Multiple regression models: Linear Regression, Ridge, Lasso, etc.  
   - Hyperparameter tuning and cross-validation  

4. **Model Evaluation**  
   - Metrics: RMSE, R² score  
   - Visualization of prediction accuracy  

5. **Prediction and Export**  
   - Generating predictions on the test set  
   - Exporting results to CSV  

## 🛠️ Requirements

You can install the required libraries with:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## 🚀 Getting Started

1. Download the dataset from the Kaggle competition page.

2. Clone this repository:
```bash
git clone https://github.com/yourusername/house-price-prediction.git
cd house-price-prediction
```

3. Open the notebook and run it step-by-step:
```bash
jupyter notebook HousePricePrediction.ipynb
```

Feel free to reach out if you have any questions or suggestions!
