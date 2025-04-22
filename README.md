# **🏠 House Price Prediction using Machine Learning**
A simple machine learning project to predict house prices based on selected features using Linear Regression.

## 📁 **Project Structure**
bash<br>
Copy<br>
Edit<br>
House-Price-Prediction-ML/<br>
│<br>
├── PRODIGY_ML_01.ipynb \t     # Main script to train and evaluate the model<br>
├── train.csv          \t      # Training dataset<br>
├── test.csv            \t     # Test dataset<br>
├── sample_submission.csv  \t  # Format for Kaggle submission<br>
└── README.md            \t    # Project documentation<br>

## **📊 Dataset**
This dataset was originally from Kaggle - House Prices: Advanced Regression Techniques. It contains information on house sales in Ames, Iowa.

- **Target variable:** SalePrice
- **Features used in model:**
- **GrLivArea:** Above ground living area (in square feet)
- **BedroomAbvGr:** Number of bedrooms above ground
- **FullBath:** Number of full bathrooms above ground<br>

## **⚙️ Model and Approach**
We used a Linear Regression model from scikit-learn for predicting house prices.

**Workflow:**
- Load and preprocess the data.
- Select relevant features.
- Handle missing values (drop rows with nulls).
- Split data into train and test sets.
- Train a linear regression model.
- Evaluate model using Mean Squared Error (MSE) and R² Score.
- Predict the price of a new house (for demo purposes).

## **📈 Sample Output**
After training the model, the script prints:<br>
bash<br>
Copy<br>
Edit<br><br>
Training MSE: 1402059616.12<br>
Test MSE: 1603942893.83<br>
Training R2: 0.718<br>
Test R2: 0.688<br>
Predicted price for the new house: $337241.52

## **▶️ How to Run**
Make sure you have Python and required libraries installed. Then run:<br>

bash<br>
Copy<br>
Edit<br>
## 📌 **Installation & Setup**  
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/House-Price-Prediction.git
   cd House-Price-Prediction
   ```
2. Install dependencies:  
   ```bash
   pip install pandas scikit-learn
   ```
3. Run the application:  
   ```bash
   python app.py
   ```
## **🔮 Future Improvements**
- Add more features to improve accuracy
- Explore models like Random Forest, XGBoost
- Feature scaling and engineering
- Create a web app with Flask or Streamlit
- Save model and serve predictions via API

## **📜 License**
This project is licensed under the MIT License for educational purposes only.
