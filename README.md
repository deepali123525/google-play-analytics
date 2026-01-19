                       Google Play Store Data Analysis – Internship Project
# Project Overview
The project belongs to my Data Analytics Internship and is aimed at analyzing the data of applications in the Google Play Store with the help of Python and Plotly.
The aim is to clean raw data, use business-oriented filters and create interactive and time-based dashboards, which will provide significant data about app performance, user interaction, and market trends.
 # Dataset Used
Play_Store_Data.csv – App-level metadata (ratings, installs, category, size, price, etc.)
User_Reviews.csv – User sentiment and subjectivity data
 # Tools & Technologies
Python 3.11
Pandas
NumPy
Plotly (Graph Objects & Express)
Jupyter Notebook
# Data Cleaning & Preprocessing
Converted ratings, reviews, installs, and prices into numeric format
Standardized app sizes into MB
Parsed date columns into datetime format
Removed invalid, missing, and inconsistent values
# Tasks & Visualizations
Task 1: Grouped Bar Chart
Average Rating vs Total Reviews (Top 10 Categories)
Filters based on rating, size, and update month
Compares quality vs engagement across categories
 Visible between 3 PM – 5 PM IST
Task 2: Choropleth Map
Global Installs by Top 5 App Categories
Displays installs geographically using country mapping
Excludes categories starting with A, C, G, S
Highlights categories with installs > 1 million
 Visible between 6 PM – 8 PM IST
 Task 3 : Dual Axis Chart
Average Installs vs Revenue (Free vs Paid Apps)
Dual-axis comparison of installs and revenue
Advanced filtering on size, revenue, Android version
Visible between 1 PM – 2 PM IST
Task 4: Time Series Line Chart
Total Installs Trend Over Time (Category Wise)
Monthly aggregation of installs
Category translation for multilingual display
Month-over-month growth analysis
Visible between 6 PM – 9 PM IST
Task 5: Bubble Chart
App Size vs Rating
Bubble size represents installs
Filters include rating, reviews, sentiment, and category
Category names translated for global readability
Visible between 5 PM – 7 PM IST
Task 6: Stacked Area Chart
Cumulative App Installs Over Time
Shows long-term growth trends
Cumulative installs and MoM growth
Multi-language category labels
Visible between 4 PM – 6 PM IST
# Key Learnings
Real-world data cleaning techniques
Advanced filtering and grouping logic
Interactive visualization using Plotly
Time-based dashboard control
Data storytelling and reporting
# Challenges Faced
Handling inconsistent data formats
Debugging Plotly dataframe mismatch errors
Managing multiple task-specific dataframes
# Solutions:
Careful dataframe isolation, debugging prints, and structured preprocessing.
# Project Structure
Copy code

# Internship_Project
│── task.ipynb
│── Play_Store_Data.csv
│── User_Reviews.csv
│── README.md

# Conclusion
This project shows that I am capable of doing end-to-end data analysis, including cleaning raw data and professional dashboard development. The assignments are related to real-life analysis and reinforce my data analysis base.

# Notes

All tasks are implemented using the same dataset as required by the internship guidelines.

The code is written in a simple and readable way with proper comments.



Author

Deepali Srivastava

Data Analytics Intern

