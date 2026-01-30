# Data Cleaning & Missing Value Handling using Pandas

## Project Overview
This project focuses on essential data preprocessing techniques used in Machine Learning and Data Science workflows. The objective is to identify, analyze, and handle missing values in a dataset to improve overall data quality and reliability.

---

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook (VS Code)

---

## Dataset
The following datasets was used:
- House Prices Dataset    

(The dataset is loaded locally in CSV format.)

---

## Tasks Performed

1. Loaded the dataset using Pandas  
2. Identified missing values using `.isnull().sum()`  
3. Visualized missing value patterns using bar charts  
4. Applied median imputation for numerical features  
5. Applied mode imputation for categorical features  
6. Removed columns with extremely high missing values  
7. Validated the dataset after cleaning  
8. Compared dataset size and quality before and after cleaning  
9. Exported the cleaned dataset  

---

## Key Observations
- The dataset was checked for missing values across all columns.
- Appropriate imputation techniques were applied where necessary.
- Data quality was improved while maintaining dataset integrity.
- The final cleaned dataset is suitable for further analysis or model training.

---

## What I Learned

While working on this project, I learned the difference between mean and median imputation and when each should be used. Mean imputation replaces missing values with the average of the column and works well when the data is normally distributed without extreme outliers. Median imputation is more robust and is preferred when the data contains outliers or is skewed, as it is not affected by extreme values.

I also learned when it is appropriate to drop rows with missing values. Rows can be removed when the number of missing values is very small or when the missing data does not carry important information. However, dropping too many rows can reduce the size of the dataset and may lead to loss of important patterns, so this step must be done carefully.

Understanding why missing data is harmful was another important takeaway. Missing values can lead to biased models, incorrect statistical calculations, and poor predictive performance. Many machine learning algorithms cannot handle missing values directly, making it necessary to clean or impute data before training a model.

I also learned about data leakage and why it is a serious issue in machine learning projects. Data leakage occurs when information from outside the training dataset is used during model training, either directly or indirectly. This leads to unrealistically high performance during evaluation but poor results in real-world scenarios. Preventing data leakage is essential for building reliable and trustworthy models.

Finally, I understood the importance of data quality in machine learning. High-quality data ensures better model performance, reliable predictions, and meaningful insights. Data quality involves accuracy, consistency, completeness, and relevance of data. Even the best algorithms cannot perform well if the input data is noisy, incomplete, or incorrect.
