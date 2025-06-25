
# task2_elevate_labs
📊 Titanic Dataset - Exploratory Data Analysis (EDA)
This notebook performs full EDA (Exploratory Data Analysis) on the Titanic dataset, focusing on understanding feature distributions, relationships, and survival patterns.

📁 Dataset Info
Rows: 891 passengers

Features: 12 columns

Target: Survived (0 = No, 1 = Yes)

✅ EDA Steps
1. Summary Statistics
Used df.describe() to analyze mean, median, std, etc.

Used df.info() and df.isnull().sum() to check missing values.

2. Missing Value Handling
Age: Filled with median.

Embarked: Filled with mode.

Cabin: Dropped (too many missing values).

3. Univariate Analysis
Histograms for Age, Fare, SibSp, Parch.

Boxplots for Age and Fare grouped by survival status.

4. Multivariate Analysis
Correlation Matrix to identify numeric relationships.

Pairplot for selected numeric features with Survived.

5. Categorical Feature Analysis
Bar plots:

Sex vs Survived

Pclass vs Survived

Embarked vs Survived

6. Feature Engineering
Extracted Title from Name column and analyzed its relation to survival.

📈 Key Observations
Women and children had higher survival rates.

Passengers in 1st class were more likely to survive.

Higher fare correlated with better survival odds.

Some outliers found in Fare and Age.

Many missing values in Cabin, removed from analysis.

🛠 Tools Used
Python 🐍

Pandas

Seaborn

Matplotlib

