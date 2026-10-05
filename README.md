Titanic — Exploratory Data Analysis

An exploratory data analysis project investigating the factors associated with passenger survival using the Titanic dataset.

The project follows a structured analytical workflow covering data cleaning, exploratory analysis, visualization, and interpretation of passenger-level patterns.

🎯 Objectives
Understand the structure and quality of the Titanic dataset
Identify factors associated with passenger survival
Analyze relationships between demographic and socioeconomic variables
Handle missing and inconsistent data
Communicate analytical findings through effective visualizations

🛠️ Technologies
Python
Pandas — data manipulation and analysis
NumPy — numerical operations
Matplotlib — data visualization
Seaborn — statistical visualization
Jupyter Notebook — interactive analysis

🔎 Analysis Workflow

1. Data Understanding
Dataset dimensions and structure
Data types and descriptive statistics
Unique-value analysis
Missing-value assessment

3. Data Cleaning
Identified missing values in key variables
Median imputation for missing Age values
Removed Cabin due to its high proportion of missing values
Prepared variables for exploratory analysis

4. Exploratory Analysis

The analysis examines the relationship between survival and:

Gender
Passenger class
Age
Family size
Fare
Embarkation point

📊 Key Findings
Overall Survival

Approximately 38% of the 891 passengers in the dataset survived.

Gender

Gender was one of the strongest factors associated with survival:

Female: ~74% survival rate
Male: ~19% survival rate
Passenger Class

Survival varied substantially across passenger classes:

Passenger Class	Approx. Survival Rate
1st Class	~63%
2nd Class	~47%
3rd Class	~24%
Age

Passengers under the age of 10 showed notably higher survival rates compared with several older age groups.

Class × Gender

The interaction between passenger class and gender revealed substantial differences in survival outcomes:

1st-class females: ~97%
3rd-class males: ~15%
Family Size

Passengers traveling alone generally had lower survival odds than passengers traveling with family members, demonstrating the importance of examining relationships between multiple variables rather than analyzing features independently.

🧹 Data Quality

Two important data-quality issues were addressed:

Age: approximately 20% missing → median imputation
Cabin: approximately 77% missing → removed from the primary analysis

These preprocessing decisions were made to improve the usability of the dataset while retaining the majority of relevant observations.
  
   
## Visualizations

### Survival by Gender
![Survival by Gender](survival_by_gender.jpg)

### Survival by Passenger Class
![Survival by Class](survival_by_class.jpg)

### Correlation Heatmap
![Correlation Heatmap](correlation_heatmap.jpg)
  
📁 Repository Contents
titanic_eda_guide1.ipynb — Complete exploratory data analysis notebook
requirements.txt — Python dependencies
survival_by_gender.jpg — Survival analysis visualization
survival_by_class.jpg — Passenger-class survival visualization
correlation_heatmap.jpg — Feature correlation visualization

🚀 Getting Started

Clone the repository:

git clone https://github.com/jagtapbhushan254-alt/titanic-exploratory-data-analysis.git
cd titanic-exploratory-data-analysis

Install dependencies:

pip install -r requirements.txt

Launch Jupyter Notebook:

jupyter notebook

Open titanic_eda_guide1.ipynb and run the notebook cells sequentially.

🔮 Future Work

Potential extensions include:

Develop a Titanic survival prediction model
Compare classification algorithms such as Logistic Regression and Random Forest
Evaluate models using appropriate classification metrics
Perform feature engineering and model interpretation

🎓 Skills Demonstrated

Data Analysis: Data Cleaning • Exploratory Data Analysis • Missing-Value Handling • Statistical Analysis

Python: Pandas • NumPy • Matplotlib • Seaborn

Analytical Skills: Pattern Identification • Feature Relationships • Data Visualization • Data Interpretation
