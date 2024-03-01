
---

# Football Data Analysis and Power BI Dashboard Project

## Project Objective

In the dynamic world of sports analytics, the ability to draw meaningful insights from game data can significantly influence strategic decisions. This project was conceived as a part of an intensive training program spanning several weeks to months, with the ultimate goal of immersing ourselves in the practical aspects of data management. Our challenge was to create precise reports for informed decision-making, using a dataset revolving around football.


## Introduction

Training Context: "After an intensive training period utilizing various tools, we were faced with a new challenge."
Project Goal: "The aim was to dive into data management practice through a concrete project, culminating in the delivery of detailed reports for enlightened decision-making around a football dataset."

## Data Discovery Phase

Database Presentation: "Our initial step involved familiarizing ourselves with an unfamiliar SQLite database using DBeaver, an SQL tool, to navigate the tables and comprehend their structure."
Data Quality Assessment: "I quickly identified data quality issues, such as matches without teams or players listed in multiple positions for a single match, leading me to sort and cleanse the data in collaboration with my instructor."

## Technical Preparation and Modelling

Datawarehouse Feeding: "With a clear understanding of the dataset, I embarked on the technical aspect, feeding a datawarehouse via Talend, considering the specific constraints of Power BI for modelling."
Data Normalization: "Normalization was necessary to split team and player information into two separate fact tables, in line with the management of filters in Power BI."
Datawarehouse Construction: "The adopted datawarehouse model was a snowflake schema, incorporating interconnected dimension tables, particularly between 'Player' and 'Player Attribute', to meet our analysis requirements."

## Power BI Implementation

Data Transformation: "Due to prior transformations, utilizing Power BI was relatively straightforward, although recreating the data model was necessary to resolve homonym issues."
Data Model Reconstruction: "Improperly named columns, like the various IDs, required special attention to properly establish links in Power BI for effective data exploration."

## Finalization and Visualization

Filters and Graphs Creation: "Implementing filters and designing graphs were key for making the data easily navigable and visually compelling."
Radar Module: "Finally, to meet a specific request from Cedric, we incorporated a complex radar module, necessitating an additional plugin download to enhance our visualizations."

## Conclusion and Questions

Summary and Discussion: "This overview captures the journey we undertook for this project. I am now open to your questions and ready to delve into any aspects you wish to explore."


![Radar des caractéristiques des joueurs](https://github.com/ArvindB75/Project-5-Football-Data-Analytics/blob/main/Power%20BI/pbi5.JPG)


## Installation Instructions

To replicate this project or explore the dataset, you will need the following tools and packages:

Power BI Desktop
DBeaver or any other SQL database management tool
Talend Open Studio for Data Integration

## How to Use the Dataset

The dataset is stored in an SQLite database file. To load the data for analysis or visualization, you can use the following SQL management tools:

```
-- Use DBeaver or similar tool to connect to the SQLite database and explore the data
SELECT * FROM table_name;
```

## Results and Conclusions

Through the creation of the Power BI dashboard, we were able to provide interactive and insightful visualizations of football data, which can assist stakeholders in making informed decisions. The radar module, in particular, adds a detailed layer of analysis for player performance assessment.

## Recommendations

Based on our project findings, the following recommendations can be made to enhance football data analysis:

Focus on Data Quality: Ensure data integrity by implementing rigorous cleansing processes before analysis.
Invest in Data Normalization: Normalize datasets to facilitate effective filtering and reporting in Power BI.
Expand Visualization Tools: Utilize advanced visualization tools like radar charts to provide a comprehensive view of player statistics.

## License and Citation

The football data utilized in this project is sourced from public domains dedicated to sports statistics. Please adhere to the specific licensing agreements of the datasets used.

## Contributions

Contributions to this project are warmly welcomed. If you're interested in contributing, please start by opening an issue to discuss your proposed changes.

## Contact

Should you have any queries or feedback regarding this project, please do not hesitate to reach out at:

abajolah@gmail.com
