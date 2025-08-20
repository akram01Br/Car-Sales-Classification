# Car Sales Classification

Predict whether a car’s sales will be **High** or **Low** using **Decision Tree** and **Random Forest**.  
Includes data preprocessing, model training, evaluation, and testing on new unseen data for generalization.

---

## Project Description

This project focuses on predicting car sales categories (High or Low) based on various features of cars using **Decision Tree** and **Random Forest** classifiers.  

**Dataset:**  
- 50,000 entries with 11 columns  
- Features include: Model, Year, Region, Color, Fuel Type, Transmission, Engine Size, Mileage, Price, Sales Volume  
- Target: Sales Classification (High / Low)  

**Steps in the Project:**  
1. **Data Cleaning and Exploration:** Checked for missing values and understood the distribution of features.  
2. **Feature Encoding:** Converted categorical features to numerical values using OneHotEncoding and Label Encoding.  
3. **Train/Test Split:** Split the data into 80% training and 20% testing.  
4. **Model Training:**  
   - Decision Tree Classifier  
   - Random Forest Classifier  
5. **Evaluation:**  
   - Calculated Accuracy, Precision, Recall, F1-score  
   - Observed potential overfitting with Decision Tree  
6. **Generalization Test:**  
   - Predicted on new, unseen car data to check model generalization  
   - Random Forest showed better generalization than a single Decision Tree  

**Key Insights:**  
- Decision Trees are simple and interpretable but prone to overfitting.  
- Random Forest reduces overfitting by aggregating multiple trees, providing better predictions on new data.  
- Always check Train vs Test vs New Data performance to evaluate model generalization.  

**Technologies Used:**  
- Python, Pandas, Scikit-learn  

---

