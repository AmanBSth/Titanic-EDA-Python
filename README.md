# Introduction

The sinking of the RMS Titanic in 1912 is one of the most infamous shipwrecks in history. The tragedy resulted in the loss of many lives, but the dataset we have contains valuable information about the passengers, which allows for a deeper understanding of the events that transpired. This project aims to explore, analyze, and visualize the Titanic dataset to uncover insights about the passengers and their survival.

# Dataset

The dataset used in this project can be found in the `train` directory. It includes the following columns:

- `PassengerId`: A unique identifier for each passenger.
- `Survived`: Whether the passenger survived (1) or not (0).
- `Pclass`: The passenger's class (1st, 2nd, or 3rd).
- `Name`: The passenger's name.
- `Sex`: The passenger's gender.
- `Age`: The passenger's age.
- `SibSp`: The number of siblings or spouses aboard.
- `Parch`: The number of parents or children aboard.
- `Ticket`: The ticket number.
- `Fare`: The fare paid for the ticket.
- `Cabin`: The cabin number.
- `Embarked`: The port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).

# Data Cleaning

This phase includes:

- Data loading and initial examination.
- Handling missing values and data cleansing.
- Descriptive statistics and visualizations to understand the data.

# Data Analysis

This phase includes:

- Survival rate analysis by different factors (e.g., gender, class).
- Exploring correlations between variables.
- Visualizing key insights, such as survival rate by age and class.
