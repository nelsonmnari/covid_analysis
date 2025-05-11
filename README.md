📊 COVID-19 Data Analysis: Focus on Germany and Global Comparisons
📝 Overview
This project analyzes the global spread and impact of COVID-19, with a focused case study on Germany. The data is sourced from Kaggle and includes key metrics like total cases, total deaths, vaccination progress, and calculated death rates.

The analysis is performed in Python using pandas, matplotlib, and Jupyter Notebook, and includes visualizations to communicate findings clearly.

🔍 Key Objectives
Analyze total COVID-19 cases and deaths in Germany over time.

Calculate the death rate in Germany (deaths / total cases).

Identify the top 5 countries with the highest COVID-19 cases.

Compare vaccination percentages among these top countries.

Visualize trends and comparisons using line plots, bar charts, and pie charts.

🇩🇪 Germany Case Study
📈 Total Cases and Deaths Over Time
Using time-series data, we plotted:

Total cases in Germany

Total deaths in Germany

These plots illustrate the progression of the pandemic and its human toll in Germany.

⚰️ Calculating the Death Rate
The death rate was calculated as:

ini
Copy
Edit
death_rate = total_deaths / total_cases
This value was tracked over time and visualized to monitor how it changed during the course of the pandemic.

🌍 Global Comparison
🏆 Top 5 Countries by Total Cases
The dataset was grouped by country and sorted by the latest total cases. The top 5 countries with the highest total COVID-19 cases were identified and displayed both as a table and in a bar chart.

💉 Vaccination Percentages
For these top 5 countries, we calculated the percentage of the population vaccinated:

ini
Copy
Edit
percent_vaccinated = people_vaccinated / population * 100
The results were visualized in a pie chart with labeled country names and vaccination percentages.

📊 Visualizations
Line plot: Total cases and deaths in Germany

Line plot: Death rate in Germany over time

Bar chart: Top 5 countries by total cases

Pie chart: % vaccinated population in top 5 countries

🧰 Tools & Libraries
pandas for data cleaning and manipulation

matplotlib for plotting

Jupyter Notebook for running and displaying code and charts

📁 Files
covid_analysis.ipynb — Jupyter Notebook with full code and plots

📌 Credits
Data source: Kaggle — Global COVID-19 dataset

