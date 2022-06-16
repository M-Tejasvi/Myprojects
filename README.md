# Myprojects

Project 1: Attribution Modeling and Budget optimization.
Description
Business Objective

Marketing is a technique of getting potential clients or customers interested in one’s products and services. Producers can reach out to their customers via various marketing channels. It looks simple by definition but is indeed a much more challenging task. Advertisers use various online marketing channels to reach consumers, and they typically want to know how much each channel contributes to their marketing success. This is what is known as multi-channel attribution. In many cases, advertisers approach this problem using simple models that help them understand the importance of each marketing channel. A few attribution models are as follows: i. Single Touch attribution models like First Touch Conversion, Last Touch Conversion ii. Multi-Touch attribution models like Linear Touch Conversion iii. Probabilistic models like Markov chains, etc We will try building all these models in our project to understand how these models will help us find which channels will lead us to more conversions. In this project, we aim to improve the advertising ROI by quantifying the actual value of the multi-faceted advertising campaigns. This will enable business stakeholders to make decisions based on the millions of converting click paths by isolating the impact of every touchpoint.

Data Description

The data is in the form of a CSV file with a data size of 586737 rows and 6 columns.
The columns are as follows: • Cookie - Anonymous customer-id 
• Time - Date and time when the visit took place 
• Interaction - Categorical variable indicating the type of interaction that took place 
• Conversion - indicating whether a conversion took place, 0: not converted, 1: converted 
• Conversion value - Value of the potential conversion event 
• Channel (target variable) - The marketing channel that brought the customer to our site

Aim
The project aims at building multiple attribution models on the given dataset to discover channels leading to greater customer conversions.

Tech stack
• Language - Python
• Libraries – numpy, matplotlib, seaborn, itertools, gekko, pandas-profiling

Approach
1. Importing the required dependencies and libraries.
2. Import the dataset.
3. Exploratory Data Analysis (EDA) –
   ▪ Create EDA report using pandas profiling python module
4. Building Single Touch Attribution Models
   ▪ Last Touch Attribution model
   ▪ First Touch Attribution model
   ▪ Last non direct Touch Attribution model
5. Building Multi-Touch Attribution Models
   ▪ Linear Attribution model
   ▪ Position based (U-shaped) Attribution model
   ▪ Position Decay Attribution model
6. Probabilistic Attribution model
   ▪ Markov Attribution model
   ▪ Shapley Value model
7. Results
   ▪ Tables – an average of all the models
   ▪ Graphs – plot the models
8. Build a Budget Optimization Engine
