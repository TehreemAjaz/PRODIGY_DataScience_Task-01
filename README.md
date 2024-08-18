# PRODIGY_DataScience_Task-01
Description of Task: Visualizing Categorical and Continuous Variables from the Titanic Dataset
In this task, we are using the Titanic dataset, which comes built-in with the seaborn library, to visualize the distribution of both categorical and continuous variables. The dataset contains information about passengers on the Titanic, including demographic information, ticket details, survival status, and more.

Step 1: Loading the Dataset
We begin by loading the Titanic dataset using sns.load_dataset('titanic'). This dataset is a pandas DataFrame containing columns such as sex, age, survived, pclass, and others.

Step 2: Visualizing the Distribution of a Categorical Variable (Gender)
To understand the distribution of gender among passengers, we create a bar chart. The sex column is categorical, containing two categories: Male and Female. We use a bar chart to show the frequency of each gender in the dataset.

Tool Used: sns.countplot()
Outcome: A bar chart that displays the count of male and female passengers on the Titanic.
This visualization helps us quickly see which gender had more passengers on board.

Interpretation:
Gender Distribution: The bar chart shows how many male and female passengers were on board the Titanic. It provides a visual summary of the gender ratio.
These visualizations are critical for understanding the composition of the Titanic passengers, which can be a starting point for more detailed analysis (e.g., survival rates by gender or age).
