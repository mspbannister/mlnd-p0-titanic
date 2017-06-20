# mlnd-p0-titanic
Udacity MLND Project 0 - Titanic Survival Exploration

This is my submission for Project 0 ('Titanic Survival Exploration') on Udacity's Machine Learning Engineer Nanodegree. The project brief asked the student to create decision functions that attempt to predict survival outcomes from the 1912 Titanic disaster, building on code provided by Udacity.

## List of files (all provided by [Udacity](https://github.com/udacity/machine-learning/tree/master/projects/titanic_survival_exploration))
- `titanic_survival_exploration.ipynb` : completed submission file (Jupyter Notebook)
- `titanic_survival_exploration.html` : completed submission file (HTML)
- `visuals.py` : supporting code (provided by Udacity)
- `titanic_data.csv` : underlying data (described below)

## Data

The dataset used in this project is included as `titanic_data.csv`, which contains the following attributes:

**Features**
- `pclass` : Passenger Class (1 = 1st; 2 = 2nd; 3 = 3rd)
- `name` : Name
- `sex` : Sex
- `age` : Age
- `sibsp` : Number of Siblings/Spouses Aboard
- `parch` : Number of Parents/Children Aboard
- `ticket` : Ticket Number
- `fare` : Passenger Fare
- `cabin` : Cabin
- `embarked` : Port of Embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)

**Target Variable**
- `survival` : Survival (0 = No; 1 = Yes)