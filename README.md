# Nikhil_Portfolio
This is my data science portfolio showcasing all my projects

## [**Project1: Political Text Classifier**](https://github.com/NikhilGaur406/Political-Text-Classifier)

I was interested in working on Natural Language Processing projects, and applying it to a political dataset, which is why I chose to work on this project. The whole point of this project is to use deep learning techniques to classify a Redditor as right or left wing. 

### **Technologies Used**

#### **Python, Pandas, Numpy, Scikit-Learn, and Tensorflow**

**Data Collection:**

Data was collected from Reddit using several right and left leaning subreddits such as Conservative, LateStageCapitalism, StuffPoliticsSays, StuffLiberalsSay, democrats, Republican, Impeach_Trump, esist, and Liberal

**Preprocessing**

- Deleted posts that had the values '[removed]', and '[deleted]'
- Deleted moderator and bot generated posts

**Modeling**

- Tried using bag of words, custom word embeddings, and BERT, with BERT performing the best
- Used Logistic Regression, Naive Bayes, and other classificaiton techniques to get best result
- Best model was Neural Network trained with 300 epochs, at batch_size of 500   

## **Political Keyword Analysis**

The goal here was to see what kind of words popped up with word cloud

- I queried entire dataset to find most common words regarding certain topics such as Trump, Biden, Covid, etc.



## [**Project2: Used Car Price Predictor**](https://github.com/NikhilGaur406/CragislistVehicles)

This project was my first attempt at a regression problem, and I aim to predict the price of a used car  on Craigslist.

### **Technologies Used**
#### Python, Pandas, Matplotlib, Scikit-learn, Numpy, Seaborn

### **Process** 

Filled in missing values, analyzed data through visuals, and created several models such as Linear Regression, Decision Tree, Random Forest, XGboost with Random Forest performing the best
 
### **About**

This is my first classification project, in which I classified whether a crime is an arrest, based on variables such as Crime Type, geographical variables (longitude, latitude, beat, district), etc.

### **Technologies Used**

Python Pandas, SQL, Matplotlib, Seaborn, Sci-kit learn, Numpy, 

## [**Project3: Crime Arrest Predictor**](https://github.com/NikhilGaur406/CrimePrediction)

### Dataset

### About

Using different variables such as geographical variables, date, type of crime, etc. to determine if that crime resulted in an arrest.
### Process

Filled missing values, feature engineered variables such as crimes_per_district, crimes_per_season, created several models such as Logistic Regression, DecisionTrees, RandomForest, etc. where RandomForestClassifier performed the best.

### Visuals

Crime Type Distribution
![Crime Distribution Image](images/Crime%20Type%20Breakdown.JPG)
