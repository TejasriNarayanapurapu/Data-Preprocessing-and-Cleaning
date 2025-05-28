# Data-Preprocessing-and-Cleaning
Data Preprocessing and Cleaning
 Data Cleaning & Preprocessing
Effective data preparation is essential for building accurate and reliable machine learning models. Below are the steps we followed to clean and preprocess the dataset:

✅ 1. Data Import & Exploration
Loaded the dataset using pandas and inspected its structure with .info(), .describe(), and .head().

Identified missing values, data types, and potential inconsistencies.

🧹 2. Handling Missing Values
Replaced missing numerical values (e.g., Age, Fare) with median or mean.

Imputed missing categorical values (e.g., Embarked) using the mode.

Dropped features like Cabin with excessive missing data.

🔁 3. Encoding Categorical Features
Applied Label Encoding for binary categorical variables (e.g., Sex).

Used One-Hot Encoding for multi-class variables (e.g., Embarked) to convert them into numerical format.

📊 4. Outlier Detection & Removal
Used boxplots and the Interquartile Range (IQR) method to detect and remove outliers in numerical columns like Fare.

⚖️ 5. Feature Scaling
Standardized numerical features (Age, Fare) using StandardScaler to normalize the data for algorithms sensitive to feature scale.

🧾 6. Feature Selection & Cleanup
Removed irrelevant or redundant columns such as Name, Ticket, and PassengerId.

Ensured the dataset was clean, structured, and ready for model building.

🔄 7. Train-Test Split
Split the processed dataset into training and testing sets using train_test_split() for model evaluation.

