# Water Potability

## 1. Goal of the project

Develop a solution to predict the potability of the water based on the different water quality metrics.

The software will be implemnted in a hand device. 

## 2. Business Understanding and Business Problem

### Company occupation
Water For All is a global NGO specialized on granting access to potable water in disadvantaged areas.

### Business Problem
Water For All  wants to create a hand device to analyze the potability of water. 

### 3. Dataset

The dataset shape is:  10 Columns & 3276 rows

| Feature 1 | Feature 2 | Feature 3 | Feature 4 | Feature 5 | Feature 6 | Feature 7 | Feature 8 | Feature 9 |
| :-----: | :---: | :---: | :-----: | :---: | :---: | :-----: | :---: | :---: |
| pH | Hardness | Solids | Organic_carbon | Turbidity | Chloramines | Sulfate | Conductivity | Trihalomethanes |

| Target |
| :-----: |
| Potability |

Data Set found in Kaggle. 
[Kaggle link](https://www.kaggle.com/datasets/adityakadiwal/water-potability?resource=download&select=water_potability.csv)

### 4. Proccess

#### 4.1 Exploratory Data Analysis



# Tools Used
* Pandas
* Numpy
* Matplotlib
* Seaborn
* Time
* scikit-learn
* statsmodels
* Trello 
* MIRO

# Resources
London bike sharing dataset
https://www.kaggle.com/hmavrodiev/london-bike-sharing-dataset

# OLS regression model performance

Train R^2: 0.628 - Train Adjusted R^2: 0.628

Test R^2: 0.655 - Test R^2: 0.582

* Difference in R^2 between train and test 2.07%
* Difference in R^2 between train and test is 4.6% which is less than 5%. 

<img src="https://user-images.githubusercontent.com/73388089/114029525-e24b9100-9879-11eb-95af-583258825ca6.png" alt="Test_VS_Prediction" width="300" height="250"> <img src="https://user-images.githubusercontent.com/73388089/114029573-f099ad00-9879-11eb-8d49-5fcd804232ed.png" alt="Test_VS_Prediction" width="300" height="250">



# Process
1. Design: 
  * I have created a MIRO board with the story mapping. https://miro.com/app/board/o9J_lRe3F5E=/
  * I have created a Trello board with the epics of requirements needed to deliver. https://trello.com/b/S7aR17IA 
2. Clean, manipulate and create the visualizations. 
  * Exploratory Data Analysis
  * Create visualizations
  * Create Dummies
  * Recursive Feature Selection (RFE)
3. Create the linear regression model. 
  * Validate the assumptions (Linearity, Autocorrelation, Sub-Normality, Normality, Multicollinearity)
4. Analyze the model perforamnce
5. Creating a Story Telling presentation 


# Presentation
To see the presentation, click in the below picture.

[<img src="https://user-images.githubusercontent.com/73388089/114032866-0492de00-987d-11eb-9609-31cb62479a73.png" alt="Test_VS_Prediction" width="400" height="330">](https://www.kaggle.com/datasets/adityakadiwal/water-potability?resource=download&select=water_potability.csv)

