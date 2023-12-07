# Analyzing Film Trends for Microsoft's New Movie Studio
**Authors:** Fanice Andayi
***
(![image.png](attachment:image.png))


# A) INTRODUCTION
In an evolving landscape where original content reigns supreme, understanding the current cinematic trends that drive box office success is paramount for Microsoft's foray into the movie industry. This analysis delves into the diverse genres and themes that have proven their commercial prowess, offering actionable insights to guide the strategic direction of Microsoft's new movie studio. By examining the recent box office hits, audience preferences, and emerging patterns in storytelling, this exploration aims to illuminate the potential pathways for Microsoft to carve its niche and thrive in this competitive arena.
# B) PROBLEM STATEMENT
Microsoft sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t know anything about creating movies. You are charged with exploring what types of films are currently doing the best at the box office. You must then translate those findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create.
# c) MAIN OBJECTIVE
The main objective is to identify prevalent box office trends and audience preferences across genres, providing strategic direction for Microsoft's new movie studio to create compelling, commercially successful films that resonate with audiences and differentiate the brand in the market.
# D) SPECIFIC OBJECTIVES
Certainly! Here are specific objectives aligned with those aspects:

1. **Top Studio Analysis:** Evaluate the leading studios .

2. **Genre Performance Assessment:** Analyze the performance of various genres ,identifying genres with consistent success and potential for growth.

3. **Budget-Revenue Dynamics:** Investigate the correlation between film budgets and revenue aiming to uncover optimal budgetary ranges that maximize profitability without compromise.
# E) NOTEBOOK STRUCTURE
1.Overview

2.Business Understanding 

3.Data Understanding

4.Data preparation/Cleaning

5.Data Analysis and Evaluation - Visualizations

6.Conclusion - Recommendations,Limitations,Next Steps.

![image.png](attachment:image.png)

## 1. Overview


This project aims to guide Microsoft's foray into the film industry by analyzing current box office trends to determine the most successful film genres. Leveraging data from box office performances, audience demographics, and critical reception, the study assesses the top-performing genres in recent years, emphasizing revenue generation, audience engagement, and market demands. Employing a mix of statistical analysis and industry research, the study unveils films that have consistently dominated the box office, garnering substantial profits and wide audience appeal. Moreover, it highlights the significance of strong storytelling, visual effects, and engaging characters in driving success within these genres. The findings recommend a strategic focus on certain genres for Microsoft's new movie studio, coupled with a dedication to high revenues, leading studios, and immersive visual experiences to maximize market penetration and profitability.

## 2. Business Understanding
The business problem at hand is Microsoft's venture into the film industry without prior expertise in movie production. The main pain point is the lack of understanding about which film genres are most successful at the box office. To address this, the analysis aims to answer key data questions:

1. **Which studio movies are most watched ?**
   - Analyzing the studios performing well enables us to better what they do and even provide a chance for collaboration regarding creating film content.

2. **Which film genres have consistently performed well at the box office in recent years?**
   - Understanding the top-performing genres provides critical insights into market trends and audience preferences, guiding Microsoft's studio toward potentially lucrative areas of production.

2. **What is the relationship between production_budgets and gross(earnings)?**
   - Analyzing revenue trends in relation to the gross(earnings) helps quantify the financial potential and profitability of specific film types, enabling informed decisions on investment allocation.



To understand the datasets we are working with we first explore our data by loading the datasets.

## 3. Data Understanding
The data utilized for this project is sourced from comprehensive databases such as the box office movies,the numbers and market research on film performances. These datasets are instrumental in addressing the data analysis questions .

1. **Data Origin and Relevance to Analysis Questions:**
   - The data primarily originate from reputable sources tracking box office performances, film genres, revenues, audience demographics, and critical reception. These sources offer insights into film success metrics relevant to understanding genre performance.

2. **Representation and Variables:**
   - The dataset encompasses a broad range of films released in recent years, including variables such as film title, release date, genre categorization, box office revenue, production budget, audience demographics (age, gender, location), critical ratings, and perhaps viewer ratings.
  
3. **Target Variable:**
   - The primary target variables are box office revenue, genre categorization, and audience demographics. Understanding how these variables interact and influence each other is crucial in shaping the studio's strategic decisions.

4. **Properties of Variables:**
   - Box office revenue and production budget typically represent continuous numerical values.
   - Genre categorization is categorical, allowing for classification and comparison of different film types.
   - Audience demographics may include categorical and numerical values, providing insights into the composition and preferences of the movie-going audience.

The dataset's richness in film-related information allows for comprehensive analysis and exploration of correlations between genres, revenues, audience characteristics, and critical reception, serving as a robust foundation for deriving actionable insights to guide Microsoft's movie studio endeavors.
We are going to be checking the data for the following:

a.Determine the number of records 

b.Preview top and bottom of our dataset

c.Check whether each column has an appropriate data type

## 4. Data Preparation/Cleaning

Describe and justify the process for preparing the data for analysis.
Questions to consider:
* Were there variables you dropped or created?
* How did you address missing values or outliers?
* Why are these choices appropriate given the data and the business problem?
Here we are going to follow the steps below for data preparation:

In preparing the data for analysis in the context of understanding successful films at the box office, several steps were taken to ensure the data's quality, relevance, and reliability. Here's an overview of the data preparation process and the reasoning behind the decisions made:

a)Checking for missing data

b)Checking for outliers

c)Checking for duplicates

Then we data clean using the following techniques:

a)Handling Missing Values:
- **Imputation:** For missing values, common strategies like  median imputation for numerical variables imputation for categorical variables  have been used. Imputation techniques were chosen based on the nature of the missing data and their potential impact on the analysis.
- **Dropping Rows or Columns:** Rows with a high percentage of missing values or lacking critical information have been dropped .

b)Outlier Treatment:
- **Identification and Adjustment:** Outliers, if detected, could skew statistical analysis. Methods like trimming, capping, or using more robust statistical techniques (e.g., winsorization) might have been employed to address extreme values that could distort insights into movie success attributes.

c)Changing data types:
During data understanding we noticed that some gross columns were Objects instead of integers/floats this needs to be rectified inorder to visualize appropriately.

The data preparation process was critical to ensuring that the subsequent analysis provided meaningful insights into successful movie attributes at the box office, guiding decision-making for Microsoft's new movie studio venture.

## Data Analysis and Evaluation
Evaluate how well your work solves the stated business problem.

***
Questions to consider:
* How do you interpret the results?
* How well does your model fit your data? How much better is this than your baseline model?
* How confident are you that your results would generalize beyond the data you have?
* How confident are you that this model would benefit the business if put into use?
***


In the context of exploring successful films at the box office, the focus was more on descriptive analysis rather than building predictive models. Here's an outline of the approach taken for analyzing the data:
The analysis focused on identifying attributes associated with box office success, aligning with the business problem of guiding Microsoft's movie studio in selecting film types.
### Analysis Approach:
1. **Exploratory Data Analysis (EDA):** Utilized statistical and visualization techniques to understand the distribution of variables, identify trends, and uncover patterns in successful movies.
   
2. **Feature Engineering:** Processed and transformed raw data, creating  combining existing movie basics and movie ratings to extract more meaningful insights. For instance, analyzing genres, ratings, and other movie attributes.

3. **Correlation and Patterns:** Investigated relations among variables to identify relationships that contribute to a movie's success at the box office.


- The insights derived from the analysis can serve as valuable guidance for Microsoft's movie studio in making informed decisions.
- Implementing strategies aligned with these insights could potentially increase the studio's chances of creating successful movies that resonate with audiences.

## 6. CONCLUSIONS
Provide your conclusions about the work you've done, including any limitations or next steps.

***
Questions to consider:
* What would you recommend the business do as a result of this work?
* What are some reasons why your analysis might not fully solve the business problem?
* What else could you do in the future to improve this project?
***
In conclusion, the analysis offers valuable insights into current box office trends, potentially aiding the decision-making process for the new movie studio. However, it's essential to continuously validate and update these insights to ensure their ongoing relevance in an ever-evolving entertainment landscape.

## RECOMMENDATIONS
As a reult of my work I would recommend Microsoft to implement the following steps as they would aid in Microsoft successful venture into creation of video content:
## 1.Work with large studios
Microsoft should aim to partner or even collaborate with established and larger film studios such as Paramount pictures/Dream Works(P/DW),Buena Vista pictures(BV) and SONY as this enhances the chance of producing movies with high revenues.
## 2.Market Analysis
Microsoft should produce the genres that are most highly rated are Adventure,Animation,Comedy,Biography,Drama,Action,Crime,Drama and are likely to bring in good returns .Monitoring of industry trends and audience preferences and performance of other movie sites to make informed decisions and adapt to its strategies for sustained success as things change and the preferences evolve with time.
## 3.Strategic investments
From our analysis we have seen that the higher the production budget , the higher the worldwide gross which is the earnings from the video content therefore it is important for Microsoft to consider strategic investments in or acquisitions of larger studios or even content from them to capitalize on their existing success and market presence and to build a diverse and successful movie portfolio .

## LIMITATIONS
Some of the reasons my analysis might not fully solve the business problem are highlighted below:
## 1.Advanced Analytics
 Employment of predictive modeling to forecast future trends and potential success factors in the movie industry could prove to be more resourceful ,detailed and even more accurate in terms of the output derived from its analysis
## 2.Temporal Context
Trends in the entertainment industry evolve rapidly. The analysis might reflect current preferences but could become outdated as audience tastes change.
## 3.Complex Factors
 Success in the movie industry involves multifaceted factors beyond data analysis, including marketing, timing, and creative aspects, which this analysis might not fully capture.
 
## NEXT STEPS
According to the analysis here are some ways to forge forward and even improve on the analysis that has been
done.In future to improve on this project ,some next steps that can be taken include:
## 1.Predictive modelling
Incorporating advanced analytics such as AI to forecast future trends and success in the film industry to be well informed and prepared for future uncertainities. 
## 2.Collaborate with other movie studios
From our analysis we could see that other studios perform better than others.Collaborating with this studios will enhance chances of producing movies with high revenues as we can capitalize on their existing success and market presence. 
## 3.Continuous analysis of the market and industry trends
Continuously monitor industry trends and audience preferences to adapt strategies for creating movies that reasonate with viewers which could give a competitive edge in the diverse and fast changing industry.
-By leveraging these insights and considering the limitations, the business could benefit from informed decision-making regarding film creation. However, continuous monitoring of industry shifts and a multidimensional approach beyond data analysis are crucial for sustained success in the dynamic movie industry.