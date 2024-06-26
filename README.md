# Data-Cleaning-and-Analytics-in-Knime
## University Project, Second Year Semester 1
### Introduction
This project involves working with a dataset containing 100,000 entries across three different financial credit score classes, each with 24 attributes. The primary objectives are to clean and prepare the data and to build two predictive models using the KNIME analytics platform. Specifically, I implemented Naïve Bayes and Random Forest models to predict the "Credit_Score" class.

Key Lessons
  - Clean the dataset based on provided instructions.
  - Divide the dataset into training and test sets.
  - Build and evaluate Naïve Bayes and Random Forest models.

The goal of this project is to equip the student with practical experience in data cleaning, data splitting, model training, and output explanation. Through this exercise, students will develop skills essential for building effective predictive models.

### Specifications
#### Part 1: Data Cleaning
  - Given 100,000 entries of "dirty data", my goal was to clean it so that the dataset can be used for modelling
![image](https://github.com/DanNgo4/Data-Cleaning-and-Analytics-in-Knime/assets/127183060/107548eb-0988-4327-9445-cde9ea9c27c4)

  - Total Workflow (can be downloaded from the .knwf file):
![image](https://github.com/DanNgo4/Data-Cleaning-and-Analytics-in-Knime/assets/127183060/1368196b-60ef-4e48-86a3-fef666bd955a)

  - Using different nodes including File Reader, Column Filter, Missing Value, Rule-based Row Filter, String Manipulation, String To Number, Math Formula, Cell Splitter, Numeric Binner and Feature Selection Loop Start (1:1), nearly 20,000 entries have been filtered and the remaining data has been properly manipulated to the desired formats.
![image](https://github.com/DanNgo4/Data-Cleaning-and-Analytics-in-Knime/assets/127183060/872e35d2-5add-40c5-90cd-5b45d2907db8)

#### Part 2: Data Prediction using Naïve Bayes and Random Forrest Models
  - Following the project's instructions, 2 predicting models have been built to predict the "Credit_Score" class of the dataset and compared to each other.
![image](https://github.com/DanNgo4/Data-Cleaning-and-Analytics-in-Knime/assets/127183060/11010da2-0cc9-43da-90a7-e2b47eaef041)

    + Naïve Bayes's results:
      ![image](https://github.com/DanNgo4/Data-Cleaning-and-Analytics-in-Knime/assets/127183060/5159cdd8-28e7-4185-bb21-f887a9f5b580)

    + Random Forrest's results:
      ![image](https://github.com/DanNgo4/Data-Cleaning-and-Analytics-in-Knime/assets/127183060/1d7304e7-af6c-48ff-b5f5-639a5ec5d928)


