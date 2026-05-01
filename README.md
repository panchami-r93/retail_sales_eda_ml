# Retail Sales – EDA and Simple ML

Exploratory data analysis (EDA) and a simple machine learning model on a supermarket retail sales dataset using Python.

## 🎯 Problem statement

Retail teams often don’t have a clear view of which product lines, branches, and cities drive most of their sales.  
The goal of this project is to explore a historical transaction-level sales dataset to understand key revenue patterns and build a simple model to predict `Sales` for each transaction.

## 💾 Dataset

A public supermarket sales dataset with fields such as:

- Date, Time
- Branch and City
- Customer type and Gender
- Product line
- Unit price, Quantity
- Tax 5%, Sales, cogs, gross income
- Rating

(Source: public dataset platform, e.g., Kaggle.)

## 🛠️ Tech stack

- Python, pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Jupyter / Google Colab

## 📊 What I did

- Cleaned and prepared the dataset (checked data types, handled duplicates, converted dates).
- Performed EDA to analyse sales distribution and sales by product line, city, and branch.
- Examined relationships such as Quantity vs Sales.
- Built a simple regression model (Linear Regression) to predict `Sales` using features like branch, city, customer type, gender, product line, unit price, quantity, and rating.
- Evaluated the model using RMSE and R², then summarised key insights and business-oriented recommendations.

## 🧠 What this can help with

- Understanding which product lines and locations contribute most to revenue.
- Supporting inventory and marketing decisions across branches and cities.
- Demonstrating end-to-end data analysis + modelling skills for data / ML internship roles.
