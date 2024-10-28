
# SQL Automated Data Cleaning & Data exploration: World life expectancy data




## Project Overview

Using the Life expectancy Dataset from Kaggle,
**I automated data cleaning transforming a messy dataset into a structured format and did an in-depth exploratory data analysis using SQL for insightful analysis.**




## Key Questions: 

1) Does the country's development status impact life expectancy?
2) Does GDP have any correlation with life expectancy?
3) How does the adult mortality rate in developed countries affect life expectancy?
4) Health sector expenditure influencing life expectancy



## Steps Taken

1) Pulled the data from Kaggle and kept the data as stagging data.
2) Created a Store Procedure to insert data, clean and standardise a real-world dataset by deleting duplicates, filling in missing values and correcting typos. Below is a screenshot stored procedure👇🏻

<img width="428" alt="1" src="https://github.com/user-attachments/assets/0b637a8f-d5c0-4f16-a56f-f489567628b1">

<img width="445" alt="2" src="https://github.com/user-attachments/assets/f45a60bb-566b-4450-aae6-98aefb0bcb02">


3.  **Automating data cleaning** by scheduling an event for store procedure(Cleaned Data) after 30 days 👇🏻

<img width="423" alt="3" src="https://github.com/user-attachments/assets/37d4ed4f-ef57-431b-a8bb-e024c1fee34c">


4) Then I performed Exploratory Data Analysis (EDA). Uncovered trends across life expectancy, GDP and adult mortality and did visualisation on Power BI.


## Key Findings

1) Developed countries have higher life expectancy due to better healthcare and higher GDP.

![WhatsApp Image 2024-10-17 at 23 29 57_90175c88](https://github.com/user-attachments/assets/8f70c394-dfb7-4986-a206-b34ee35b17d2)

![WhatsApp Image 2024-10-17 at 23 29 57_b53ac27d](https://github.com/user-attachments/assets/5c066b44-bdeb-498a-b4e2-6ba2f4274b85)


2) **Positive Correlation:** Higher GDP per capita strongly correlates with longer life expectancy.

![WhatsApp Image 2024-10-17 at 23 29 58_6eb42dc6](https://github.com/user-attachments/assets/61527cf4-d3c7-418a-b8d1-601ff4aba8a0)

![WhatsApp Image 2024-10-17 at 23 29 58_c768c5d1](https://github.com/user-attachments/assets/f96a8990-76c3-4506-8d06-c75fec4a7a63)


3) **Inverse Relationship:** Higher adult mortality is tied to lower life expectancy, especially in developing countries. As can be seen in result grid.

![WhatsApp Image 2024-10-17 at 23 30 00_7b7c99cc](https://github.com/user-attachments/assets/4a48ea09-8ae6-44bb-8d00-d9c22cbb75a3)

![Screenshot 2024-10-29 004846](https://github.com/user-attachments/assets/e20da463-ef58-4ad2-9a92-f1924b3cdb09)


4) Developed countries spending more in the health sector leads to better life expectancy.

![WhatsApp Image 2024-10-17 at 23 30 01_aa9eb37e](https://github.com/user-attachments/assets/383d3cf6-6103-43d6-b20a-67b8c558b320)

![Screenshot 2024-10-29 010720](https://github.com/user-attachments/assets/20798ccb-9825-4ff5-b700-8e40dd389f88)


## Recomendations

Developed countires have higher GDPs therefore they invest more in the health sector leading to better life expectancy.

