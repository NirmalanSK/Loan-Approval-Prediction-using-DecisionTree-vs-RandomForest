# Loan Approval Prediction using Decision Tree vs Random Forest  

##  Project Overview  
This project aims to predict whether a loan application will be approved or not using machine learning models. We compare two popular classification algorithms: **Decision Tree** and **Random Forest**, and evaluate their performance.  

##  Dataset  
The dataset contains information about loan applicants, such as:  
- Applicant Income  
- Coapplicant Income  
- Loan Amount  
- Loan Term  
- Credit History  
- Gender, Education, Marital Status, Employment, etc.  

The **target variable** is:  
- `Loan_Status` → Whether the loan is approved (`Y`) or not (`N`).  

##  Technologies Used  
- **Python**  
- **Pandas** – Data manipulation  
- **NumPy** – Numerical computations  
- **Matplotlib / Seaborn** – Data visualization  
- **Scikit-learn** – Machine learning models  

##  Project Workflow  
1. **Data Loading & Cleaning**  
   - Handle missing values  
   - Encode categorical variables  
   - Normalize numerical features (if needed)  

2. **Exploratory Data Analysis (EDA)**  
   - Visualize distributions  
   - Check correlations  
   - Analyze patterns between features and loan approval  

3. **Model Building**  
   - Train a **Decision Tree Classifier**  
   - Train a **Random Forest Classifier**  

4. **Model Evaluation**  
   - Accuracy Score  
   - Confusion Matrix  
   - Classification Report (Precision, Recall, F1-score)  
   - Feature Importance Analysis  

5. **Comparison**  
   - Compare Decision Tree vs Random Forest performance  
   - Discuss pros & cons of both models  

##  Results  
- **Decision Tree**: Simpler, interpretable, but prone to overfitting.  
- **Random Forest**: More accurate and robust due to ensemble learning.  
- Final metrics and comparison plots are included in the notebook.  


##  Future Improvements  
- Hyperparameter tuning with RandomizedSearchCV 
- Try other models like Logistic Regression, XGBoost, or Neural Networks  
- Build a Streamlit web app for interactive predictions  

##  Installation & Usage  
1. Clone this repository:  
   ```bash
   git clone https://github.com/your-username/Loan-Approval-Prediction.git
   cd Loan-Approval-Prediction

