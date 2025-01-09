# 911-Calls-Data-Capstone-Project
911 Calls Data Capstone Project analyzes 911 call data from Montgomery County, sourced from Kaggle. It identifies trends in emergencies (EMS, Fire, Traffic) using Python. Key insights include temporal trends (hourly, daily, monthly), geographic hot spots, and advanced visualizations with tools like Pandas, Seaborn, and Matplotlib.
This project focuses on analyzing 911 call data from Montgomery County, sourced from Kaggle. It explores trends, identifies patterns, and visualizes insights to better understand emergency call dynamics.

The dataset includes critical information such as location (latitude, longitude, zip code), time (timestamp), and call details (description, title, township, and address). Through Python and its powerful data analysis libraries, the project derives actionable insights and creates compelling visualizations.

Key Features:
Reason Analysis:
The dataset's "title" column contains information about the emergency call's reason (EMS, Fire, or Traffic). A new "Reason" column was created to categorize and analyze the most common causes for 911 calls. Visualizations using Seaborn reveal the frequency of calls by reason.

Temporal Trends:
By converting the "timeStamp" column into datetime objects, the project uncovers trends by hour, day, and month. For example, the busiest times and days for calls are highlighted through plots like count plots and line graphs.

Geographic Insights:
Analysis of the top zip codes and townships for 911 calls helps identify areas with the highest call volumes. This geographic data can inform resource allocation for emergency services.

Advanced Visualizations:
Heatmaps and clustermaps illustrate call frequency over time, providing an intuitive representation of data patterns.

Tools and Technologies:
Python: The core programming language used for analysis.
Pandas & NumPy: For data cleaning, manipulation, and aggregation.
Matplotlib & Seaborn: For creating a variety of plots and visualizations.
Google Colab: The development environment, enabling seamless collaboration and execution of the project.
This project demonstrates expertise in exploratory data analysis (EDA), visualization, and extracting meaningful insights from real-world data. It showcases how Python can be used effectively to address data-driven challenges in emergency services.
