# U.S. Medical Insurance Costs Analysis #
## :pushpin: Project Description ## 
This project analyses a dataset of U.S. medical insurance costs using Python. The dataset, **insurance.csv**, contains information on patients' demographics, health status, and insurance charges. The goal is to extract insights by applying Python fundamentals, including data handling, statistical analysis, and grouping techniques.

This project is **a work in progress** and will be continuously improved as I develop my skills. Future updates will explore more advanced analysis and potential predictive modelling.

For now, I will be using only the **csv** module to read and process the data without additional libraries like pandas.  


## :bar_chart: Dataset Information ##
The dataset includes the following columns:

**Age**: Patient's age
**Sex**: Male or Female
**BMI**: Body Mass Index
**Children**: Number of children/dependants
**Smoker**: Yes or No
**Region**: U.S. geographical region
**Charges**: Yearly medical insurance costs (USD)

The dataset is clean, with no missing data.  


## :dart: Project Goals ##
This dataset could be analysed in **many different ways**, depending on the goal. 
The following are just some of the questions I have chosen to explore, primarily as a way to **practice data analysis and Python fundamentals**:
1. Where is the majority of people in this dataset from?
2. What is the difference in insurance costs between smokers and non-smokers?
3. What is the average age of someone with at least one child?
4. What region has the lowest insurance charges for young females (aged 20-29)?

Additionally, a dictionary structure was created to store patient data by unique ID, which allows for more flexible data exploration.  

## :hammer_and_wrench: How the Code Works ##
### :one:  Loading the Data ###
- Uses Python's *csv* module to load **insurance.csv** into a dictionary format.
- Converts numerical data (age, BMI, children, charges) to floats.

### :two: Descriptive Statistics Class ###
- Calculates **mean, min, max, and median** for numerical columns.
- Generates reports summarising these statistics.

### :three:  Grouping Data ###
- Groups patients by **age range, sex, smoker status, number of children, and region**.
- Outputs summary reports with counts per group.

### :four: Drawing Insights ###
- Uses filtering and calculations to answer key questions.
- Identifies trends such as cost differences between smokers and non-smokers.  

  
## :chart_with_upwards_trend: Results & Insights ##
- The majority of patients are from the **Southeast** region.
- Smokers pay significantly **higher** insurance costs than non-smokers.
- The **average age** of a patient with **at least one child** is **39.78 years**.
- The **Southwest** region has the lowest average insurance charges for young females aged 20-29.  

  
## :rocket: Future Improvements ##
As I continue learning, I plan to enhance this project by:
- Expanding the scope of analysis to explore more relationships in the dataset.
- Implementing more efficient data handling techniques.
- Incorporating data visualisations for better insights.
- Potentially using additional libraries (e.g., pandas, matplotlib) to improve workflow.
- Introducing predictive analysis, such as estimating insurance costs based on patient characteristics.  

  
## :raised_hands: Acknowledgements ##
- [Codecademy](https://www.codecademy.com/learn) for providing the dataset.
- This project is a **work in progress**, and improvements will be made over time.    


:pushpin: **Note:** Feedback and suggestions for improvement are welcome!
