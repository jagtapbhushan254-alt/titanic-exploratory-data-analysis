🚢 Titanic — Exploratory Data Analysis

Exploring the factors associated with passenger survival through data cleaning, exploratory analysis, and visualization.

🎯 Project Overview

This project performs Exploratory Data Analysis (EDA) on the Titanic dataset to identify demographic, socioeconomic, and travel-related factors associated with passenger survival.

The analysis follows a structured data workflow:

Data Understanding → Data Cleaning → Exploratory Analysis → Visualization → Insights

🎯 Objectives

Understand the structure and quality of the Titanic dataset
Identify factors associated with passenger survival
Analyze relationships between demographic and socioeconomic variables
Handle missing and inconsistent data
Communicate findings through effective data visualizations

🛠️ Technologies & Tools
Category	Technologies
Programming	Python
Data Analysis	Pandas, NumPy
Visualization	Matplotlib, Seaborn
Environment	Jupyter Notebook

🔎 Analysis Workflow
1. Data Understanding
Dataset dimensions and structure
Data types and descriptive statistics
Unique-value analysis
Missing-value assessment

2. Data Cleaning
Identified missing values across relevant variables
Applied median imputation to missing Age values
Removed Cabin from the primary analysis due to its high proportion of missing values
Prepared variables for exploratory analysis

3. Exploratory Data Analysis

The analysis examines relationships between survival and:

Gender
Passenger class
Age
Family size
Fare
Embarkation point

4. Data Visualization

Visualizations were used to identify patterns and relationships that may not be immediately apparent from summary statistics.

📊 Key Findings

1. Overall Survival Rate

Approximately 38% of the 891 passengers in the dataset survived.

2. Gender Was a Strong Factor

Survival rates differed substantially by gender:

Gender	Approx. Survival Rate
Female	~74%
Male	~19%

3. Passenger Class Had a Major Impact

Survival also varied considerably across passenger classes:

Passenger Class	Approx. Survival Rate
1st Class	~63%
2nd Class	~47%
3rd Class	~24%

4. Age and Survival

Passengers under 10 years old showed notably higher survival rates compared with several older age groups.

5. Class × Gender Interaction

Combining multiple variables revealed even larger differences in survival outcomes:

1st-class females: ~97% survival rate
3rd-class males: ~15% survival rate

This demonstrates the importance of examining interactions between features, rather than analyzing variables independently.

6. Family Size and Survival

Passengers traveling alone generally had lower survival odds than passengers traveling with family members.

This suggests that family-related variables can provide additional context when analyzing survival patterns.

🧹 Data Quality & Preprocessing

Two major data-quality issues were addressed:

Variable	Issue	Treatment
Age	~20% missing	Median imputation
Cabin	~77% missing	Removed from primary analysis

These preprocessing decisions helped maintain the usability of the dataset while retaining the majority of relevant observations.
  
   
## Visualizations

### Survival by Gender
![Survival by Gender](survival_by_gender.jpg)

### Survival by Passenger Class
![Survival by Class](survival_by_class.jpg)

### Correlation Heatmap
![Correlation Heatmap](correlation_heatmap.jpg)
  
📁 Repository Structure
titanic-exploratory-data-analysis/
│
├── titanic_eda_guide1.ipynb
├── survival_by_gender.jpg
├── survival_by_class.jpg
├── correlation_heatmap.jpg
├── requirements.txt
└── README.md

🚀 Getting Started

1. Clone the repository
git clone https://github.com/jagtapbhushan254-alt/titanic-exploratory-data-analysis.git
cd titanic-exploratory-data-analysis

2. Install dependencies
pip install -r requirements.txt

3. Launch Jupyter Notebook
jupyter notebook

Open:

titanic_eda_guide1.ipynb

and execute the notebook cells sequentially.

🔮 Future Work

Potential extensions of this project include:

Develop a Titanic survival prediction model
Compare Logistic Regression and Random Forest
Evaluate models using appropriate classification metrics
Perform additional feature engineering
Analyze model feature importance and interpretability
🎓 Skills Demonstrated

Data Analysis
Data Cleaning • Exploratory Data Analysis • Missing-Value Handling • Statistical Analysis

Python
Pandas • NumPy • Matplotlib • Seaborn

Analytical Skills
Pattern Identification • Feature Relationships • Data Visualization • Data Interpretation

📌 Project Context

This project demonstrates foundational capabilities in data analysis, visualization, and analytical reasoning, supporting my broader interests in Data Analytics, Data Science, Machine Learning, and Information Systems.
