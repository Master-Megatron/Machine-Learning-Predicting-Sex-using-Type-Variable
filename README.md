# Predicting Sex Using Type Variable

This project is a Python reimplementation of Exercise 27.5 from Rafael Irizarry’s *Introduction to Data Science* book.  
The goal is to predict a person's sex (Male/Female) using the `type` variable (`inclass` or `online`) derived from the `reported_heights` dataset.

## Project Overview
The dataset `reported_heights.csv` contains the following columns:
- **time_stamp**: Date and time when the data was recorded  
- **sex**: Male or Female  
- **height**: Height value reported by participants  

Students who submitted data during the lecture (2016-01-25 08:15–08:30) are labeled as **inclass**, while others are labeled as **online**.  
Using this `type` variable, the model predicts `sex` and evaluates its performance.

## Workflow
1. Data loading and cleaning  
2. Feature engineering (`type` variable creation)  
3. Train-test split  
4. Logistic Regression modeling  
5. Evaluation using:
   - Confusion matrix  
   - Accuracy  
   - Sensitivity  
   - Specificity  
6. Prevalence analysis (percentage of females)

## Tools and Libraries
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib / Seaborn  

## Results
The project demonstrates that the `type` variable is predictive of sex, with in-class students more likely to be male, and online students more balanced.

## Author
**Master Megatron**  
GitHub: [https://github.com/mastermegatron](https://github.com/mastermegatron)
