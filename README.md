Google Play Store Data Analysis Project

About This Project

This project was done as part of my Data Analytics Internship.
The main goal of this project is to analyze Google Play Store app data using Python and create different visualizations based on given conditions.

I have used the same dataset that was provided during training and extended it further to complete all internship tasks.

Datasets Used


Play Store Data.csv

This dataset contains information about apps such as app name, category, rating, reviews, installs, size, price, Android version, and last updated date.

User Reviews.csv

This dataset contains user reviews along with sentiment polarity and sentiment subjectivity values.

Both datasets were cleaned and merged wherever required.

Tools and Libraries Used


Python

Pandas

NumPy

Plotly

Datetime

Pytz


Tasks Completed


Task 1 Grouped Bar Chart
In this task, I created a grouped bar chart to compare average rating and total reviews for top app categories after applying required filters.
This graph is visible only between 3 PM and 5 PM IST.

Task 2 Category Based Visualization
In this task, app installs were analyzed for the top categories after excluding specific category names.
Categories with installs greater than 1 million were highlighted.
This graph is visible only between 6 PM and 8 PM IST.

Task 3 Dual Axis Chart Free vs Paid Apps
This task compares average installs and average revenue for free and paid apps.
Multiple conditions such as installs, revenue, Android version, app size, content rating, and app name length were applied.
This graph is visible only between 1 PM and 2 PM IST.

Task 4 Time Series Analysis
This task shows the trend of total installs over time for selected app categories.
Some category names were translated into different languages for display.
The chart helps in identifying growth trends over months.
This graph is visible only between 6 PM and 9 PM IST.

Task 5 Bubble Chart
In this task, a bubble chart was used to analyze the relationship between app size and average rating.
Bubble size represents the number of installs.
Sentiment subjectivity from user reviews was also considered.
The Game category was highlighted using a different color.
This graph is visible only between 5 PM and 7 PM IST.

Task 6 Stacked Area Chart
This task visualizes cumulative installs over time using a stacked area chart.
Only high rated apps and selected categories were included.
Category names were translated into different languages in the legend.
This graph is visible only between 4 PM and 6 PM IST.

Time Based Logic

Each visualization is designed to appear only during a specific time window in IST.

If the code is run outside the allowed time range, the graph is not displayed and a message is shown instead.


How to Run the Project


Clone the repository

Install required libraries
pip install pandas numpy plotly pytz

Run the Python file
python tasks.py

Run the file during the correct time window to view each graph

Notes

All tasks are implemented using the same dataset as required by the internship guidelines.

The code is written in a simple and readable way with proper comments.


Author

Deepali Srivastava

Data Analytics Intern
