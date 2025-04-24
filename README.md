This project focuses on cleaning and preprocessing the Titanic dataset as part of a data science internship. The goal was to prepare raw data for machine learning by handling missing values, encoding categorical variables, normalizing numerical features, and removing outliers.

The process began by loading the dataset using Pandas and exploring its structure with basic functions like .info() and .isnull().sum(). Missing values in the 'Age' column were filled using the median, while missing entries in 'Embarked' were replaced with the mode. The 'Cabin' column was dropped due to a high percentage of missing data.

Categorical variables such as 'Sex' and 'Embarked' were converted into numerical format using one-hot encoding to ensure compatibility with machine learning algorithms. Feature scaling was applied to 'Age' and 'Fare' using StandardScaler to standardize values and improve model performance.

Outliers, especially in the 'Fare' column, were identified using boxplots and removed using the Interquartile Range (IQR) method to prevent skewing the data. The result was a clean, structured dataset ready for training.

The final deliverables include a Python script or notebook, the Titanic CSV file, and documentation. This project highlights essential data preprocessing techniques that are critical in building reliable machine learning models
