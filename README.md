# Challenge7_Repo
Build a financial database and web application by using SQL, Python, and the Voilà library to analyze the performance of a hypothetical fintech ETF.


## User Story
Role: PropTech Analyst

Goal: The project goal is the following parts:
• Analyze a single asset in the ETF
• Optimize data access with advanced SQL queries
• Analyze the ETF portfolio
• Deploy the notebook as a web application


Reason: The company wants to have a trial of this offering in the San Francisco real-estate market. If the service proves popular, they can then expand to other markets.

## General information about the analysis
• Compare the average prices by neighborhood.
• Build an interactive neighborhood map.
• Compose data story on:
      . trend in rental income growth compared to the trend in sales prices
      . share insights with the company about the potential one-click, buy-and-rent strategy that they're pursuing
      . establish whether neighborhoods exist for viable investments and why

## Technology
Python
Jupyter notebook that contains data preparation, analysis, and visualizations  
GitHub repository 
Pyviz development environment

## Libraries used in the analysis
• Three DataFrame imported from a CSV files with housing per year, neighborhoods cordinates and sfo neighborhood census. 
. The following libraties were imported import pandas as pd, import hvplot.pandas, from pathlib import Path, import numpy as np, import os, and %matplotlib inline

## Analysis
The data story was composed based on the data analysis and visualisation generated using the hvplots and geoviews. 