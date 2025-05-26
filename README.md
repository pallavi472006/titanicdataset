# titanicdataset
The goal of this task is to clean and preprocess the Titanic dataset to prepare it for machine learning models. This includes handling missing data, encoding categorical variables, scaling features, and detecting/removing outliers. Tools Used Python Pandas NumPy Matplotlib & Seaborn Scikit-learn Dataset Name: Titanic Dataset Source: Kaggle - Titanic Dataset

What I Did (Steps Performed) Looked at the Data First, I loaded the Titanic dataset and explored what kind of data it had — like which columns had missing values, what types of data were present, and how the data looked overall. Filled in the Missing Blanks Some columns had missing information (like Age or Embarked), so I filled them in: For numbers (like Age), I used the median value

Made the Numbers Scale Together Some numbers (like Fare) were much larger than others (like Age), which can confuse models. I scaled them down so they’re on a similar level using a technique called standardization. Checked for Odd Data (Outliers) I used boxplots to spot any unusual values that looked far off from the rest (like very high fares). I then removed those extreme outliers to keep the data clean and balanced.

