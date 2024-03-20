# DFA-2023-Datathon-Challenge-for-Data-Analysis
Data Fest Africa 2023 Datathon Challenge 20th Place Solution. <https://tinyurl.com/DFALeaderboard>

Our 20th rank consisted of the cumulative scores from the three (3) datathon challenges. It was a three (3) member team, but we could not participate in the data engineer challenge because we didn't have a female team member.

Team Trail Blazers: This repository contains the data analysis project for the 2023 DataFest Africa Datathon organised by Data Community Africa on Diceytech, from 30th September to 1st October 2023 that I attempted. 
<https://portfolio.diceytech.co.uk/project-opportunity/1694032685679x620868876154437600>

AgResources Inc. is poised for expansion and strategic investment in its farms. The vast data collated over the years is a treasure trove to carve out the company's future direction. But decisions must be precise, deliberate, and data-driven.


## Objective of the Project
To extract in-depth insights and recommendations that will shape the company's strategic plans for the coming years.

## Tools & Resources
PowerBI was my tool of choice. I connected to the data given via Snowflake using the Server, Warehouse and other necessary info. provided, and given it was my first attempt a quick tutorial on YouTube made it easy.
![Snowflake](https://github.com/MilaarAdedayo/DFA-Datathon-Challenge-for-Data-Analysis/assets/101608507/3b9a82f4-1ff8-4f58-9cf3-cbd8ae0facfd)



**Data Validation Process**
The data had 13 tables provided, and a quick cleaning process was carried out on the data consisting of over 2 million rows.
The empty or null datasets that appeared were either taken care of with the fill-up or find-and-replace menus.
IRRIGATION TABLE - for the irrigation method column, null values are found and replaced with the maximum WC-4
PEST TABLE - both  pest_description and pest_severity columns are filled up
WEATHER TABLE - the weather condition column is filled up.

Data modelling was done to the best of my knowledge as I linked the timestamps in tables relevant to each other to have facts and dimension tables. According to my modelling, I deduced that there were two facts tables.

I provided data visualizations for more than 2 of the business requirements for the challenge.
![BizReq1](https://github.com/MilaarAdedayo/DFA-Datathon-Challenge-for-Data-Analysis/assets/101608507/85ad966e-6d68-4629-8dcf-aaa3a2cb80f6)

![Req 6](https://github.com/MilaarAdedayo/DFA-Datathon-Challenge-for-Data-Analysis/assets/101608507/2cc8f890-a119-4515-9550-a28e16e0d3f4)
