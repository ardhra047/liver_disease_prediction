## 🔬 Project Pipeline

### 1️⃣ Problem Definition
- Predict whether a patient has liver disease (classification problem)
- Focus on minimizing false negatives → High Recall (critical in healthcare)

### 2️⃣ Data Collection
- Dataset with 582 patient records & 11 medical features
- Target: Liver Disease (Yes/No)

### 3️⃣ Data Preprocessing
- Handled missing values (Albumin & Globulin Ratio)
- Encoded categorical feature (Gender)
- Removed duplicates
- Applied feature scaling (for SVM, KNN)

### 4️⃣ Exploratory Data Analysis (EDA)
- Univariate analysis (feature distributions)
- Bivariate analysis (feature vs target)
- Correlation heatmap
- Identified key patterns (e.g., bilirubin vs disease)

### 5️⃣ Feature Engineering
- Selected important medical features
- Handled imbalance using model-based approach (no SMOTE)

### 6️⃣ Model Building
Trained multiple models: 
- Decision Tree  
- Random Forest  
- Gradient Boosting  

### 7️⃣ Model Evaluation
Evaluated using:
- Accuracy  
- Precision  
- Recall   
- F1-score  (**Primary Focus**)

### 8️⃣ Hyperparameter Tuning
- Applied Random Search on Gradient Boosting
- Optimized model performance

### 9️⃣ Final Model Selection
- ✅ **Gradient Boosting selected**
- Reason: Best performance 

### 🔟 Results
The model achieved 100% recall, making it highly effective for identifying liver disease cases without missing critical patients.

🛠️ Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

📁 Project Structure
liver-disease-prediction/
│
├── data/
├── notebooks/
├── images/
├── README.md

🚀 Future Improvements
Deploy as a web app using Streamlit
Add more advanced models (XGBoost, Neural Networks)
Improve accuracy while maintaining high recall

👨‍💻 Author
Ardhra k


