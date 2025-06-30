# 🧮 Sure Tomorrow – Machine Learning and Data Obfuscation for Insurance

## 🔍 Project Functionality  
This project was developed for **Sure Tomorrow**, an insurance company aiming to explore the use of machine learning for four key tasks:

1. **Customer Similarity** – Find clients with similar behavior for marketing purposes.  
2. **Binary Classification** – Predict whether a customer is likely to receive insurance benefits.  
3. **Regression** – Predict the exact amount of insurance benefits.  
4. **Data Obfuscation** – Protect sensitive information using linear algebra, while preserving model performance.

Each task explores both the **statistical foundations** and **machine learning implementation**, with a strong focus on **data transformation** and **model integrity**.

## 🛠️ Technologies and Methods  
- **Python** (NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn)  
- **Exploratory Data Analysis (EDA)**:
  - Distribution analysis of income, benefits, and family size  
  - Pairplots to visually assess groupings  
- **Task 1 – Similar Clients**:
  - Distance-based similarity using **Manhattan distance**  
  - **Feature scaling** to ensure proper comparison  
- **Task 2 – Classification**:
  - Binary classification with **K-Nearest Neighbors** (KNN)  
  - **F1-score** for model evaluation  
  - Comparison against dummy classifier baseline  
- **Task 3 – Regression**:
  - Custom implementation of **Linear Regression** using linear algebra  
  - **Root Mean Squared Error (RMSE)** for evaluation  
  - Comparison of scaled vs. unscaled features  
- **Task 4 – Data Obfuscation**:
  - Secure transformation via multiplication with an **invertible matrix**  
  - Verification that prediction quality remains unchanged  
  - Ensures **privacy without degrading model performance**

## 📈 Key Findings and Conclusion  
- **KNN** performed significantly better on **scaled data**, as unscaled features distorted distance-based predictions.  
- **Linear Regression** achieved stable results, with moderate improvements after scaling.  
- **Data obfuscation through matrix transformation** maintained model performance while anonymizing the dataset, making it a valid method for privacy protection.  
- These findings demonstrate that **simple models**, when paired with proper **preprocessing** and **data protection techniques**, can be both powerful and secure.

✅ **Conclusion**: Sure Tomorrow can confidently use machine learning to enhance customer experience and internal processes, while applying **data masking techniques** to comply with privacy standards.
