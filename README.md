Fast Food Restaurants Analysis (SQLite + Python)
About the Project

This is a small project where I analyzed the Datafiniti Fast Food Restaurants dataset using SQLite and Python.
I wanted to see which brands and cities dominate, where new outlets could do well, and how fast food has been expanding over the years.

I used:

SQLite for storing and running queries

Pandas to work with SQL results in Python

Matplotlib & Seaborn to make simple graphs

Jupyter Notebook for running everything step by step

What I Tried to Find Out
Case 1: Top Cities

Which cities have the most outlets?
Result: Houston is on top with 100+ outlets, followed by Las Vegas and Phoenix.

Case 2: States With Fewer Outlets

Which states are least crowded?
Result: Alabama, Rhode Island, and Vermont have very few outlets, which could mean less competition.

Case 3: Missing Data

Are there missing city values in the dataset?
Result: A few cities were missing. I replaced them with "Unknown".

Case 4: Spread Across the US

Do most cities have a similar number of outlets?
Result: On average, cities have only 3–4 outlets. But some small towns have just 1, while big cities cross 100+.

Case 5: Cities Above Average

Which cities have more outlets than the average?
Result: Major hubs like Houston, Las Vegas, Phoenix, and New York clearly stand out.

Case 6: Top Brands

Which restaurant brands dominate nationwide?
Result: McDonald’s, Subway, and Starbucks are the clear leaders.

Case 7: Outlets Over Time

How has the number of outlets changed over time?
Result: There’s a visible rise after 2010, showing fast food demand has been increasing.

Case 8: City & State Report

Can we make a neat table of top outlets by city and state?
Result: Yes, I built a report with aliases so it’s easy to read.

Case 9: New York City

Which brands dominate NYC?
Result: McDonald’s and Subway lead in New York, with Dunkin’ Donuts close behind.

Visuals I Made

Bar charts → top cities, top brands, state comparisons

Line chart → how outlets grew year by year

Simple tables → grouped counts, handling missing values