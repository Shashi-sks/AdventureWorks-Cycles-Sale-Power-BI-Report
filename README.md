# Business Intelligence Analyst - Sale Dashboard (Power-BI-Report)
### Project Overview

As a Business Intelligence Analyst at AdventureWorks, the goal of this project is to provide the management team with insights on key performance indicators (KPIs), regional performance, product-level trends, and customer segmentation.

###

This repository contains the code and documentation for the Business Intelligence (BI) analysis conducted for AdventureWorks, a global manufacturing company that produces cycling equipment and accessories.

### Objectives

- **Track KPIs**: Sales, revenue, profit, and returns.
- **Compare Regional Performance**: Visualize and compare performance across different regions.
- **Analyze Product-Level Trends**: Identify trends in sales across various product categories.
- **Identify High-Value Customers**: Segment customers and calculate customer lifetime value (CLV).


### Usage

- **KPI Dashboard**: Provides insights into sales, revenue, profit, and returns over time.
- **Regional Performance**: Allows comparison of sales performance across different regions.
- **Product Trends**: Analyzes product-level sales trends and seasonal patterns.
- **Customer Insights**: Identifies high-value customers and their purchasing behavior.

### Steps followed 
- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors & empty values were present except column named " BirthDate & prefix" in coustmer Lookup csv.
      
- Step 5 : List measure created. 

<img width="332" alt="image" src="https://github.com/user-attachments/assets/2b943ecc-229d-4df3-b00e-5215f52a79f8">

<img width="281" alt="image" src="https://github.com/user-attachments/assets/4035afec-8db0-44ea-bdde-975c2b0b4362">


### Following DAX expression was written for the above measure .
        
<img width="173" alt="image" src="https://github.com/user-attachments/assets/ae3dddf7-4354-47e1-9871-b3af5f7dea9e">
<img width="193" alt="image" src="https://github.com/user-attachments/assets/3b8e2eed-9c6b-48b5-a3d9-2b95855df416">
<img width="415" alt="image" src="https://github.com/user-attachments/assets/3cf857a0-1ccc-4ecb-92c9-5e4ae07d5d53">
<img width="342" alt="image" src="https://github.com/user-attachments/assets/08cfd502-c61d-4469-b7ca-2544e3c9f58c">
<img width="226" alt="image" src="https://github.com/user-attachments/assets/4c3b4f67-b614-44d6-b405-fa0bbf7782de">
<img width="262" alt="image" src="https://github.com/user-attachments/assets/2dcbc497-f30f-45a2-ad6b-e0d98c73cb4b">
<img width="303" alt="image" src="https://github.com/user-attachments/assets/13aa1797-cd5e-4c16-aa29-c146d07b0fe9">
<img width="273" alt="image" src="https://github.com/user-attachments/assets/04d090bd-6220-4b95-91e1-7870596d5b3d">
<img width="423" alt="image" src="https://github.com/user-attachments/assets/c84d2dfc-fa7f-48f4-b6ca-677a3d25220f">
<img width="418" alt="image" src="https://github.com/user-attachments/assets/6f7f1917-ca2e-4a71-81d6-0747968fe5ec">
<img width="419" alt="image" src="https://github.com/user-attachments/assets/7c14135e-0aa6-44c7-a059-8c6f82f02573">
<img width="307" alt="image" src="https://github.com/user-attachments/assets/c79b9741-3134-499a-ba03-c45cf89926fd">
<img width="261" alt="image" src="https://github.com/user-attachments/assets/058ba82e-b31e-43ba-a665-328c9e4de06d">
<img width="289" alt="image" src="https://github.com/user-attachments/assets/b96df90f-c231-44d8-addc-bb02404ec673">
<img width="282" alt="image" src="https://github.com/user-attachments/assets/dbade160-05ec-4de3-846f-1d1e66b26135">
<img width="290" alt="image" src="https://github.com/user-attachments/assets/3645664e-d485-4d22-a858-4d602e606035">
<img width="310" alt="image" src="https://github.com/user-attachments/assets/6c1e3ca9-bb3b-4acf-81cc-755b2026f29d">
<img width="228" alt="image" src="https://github.com/user-attachments/assets/ae1065e2-1f95-4755-aee4-410b1ef9e7a4">
<img width="321" alt="image" src="https://github.com/user-attachments/assets/318749fb-7e55-4e3e-9f11-e663c9c6874a">
<img width="264" alt="image" src="https://github.com/user-attachments/assets/7b467872-a924-4fe9-bb43-07b1faa78193">
<img width="238" alt="image" src="https://github.com/user-attachments/assets/efd55128-9ae7-4445-a676-88aa73f39b3c">
<img width="263" alt="image" src="https://github.com/user-attachments/assets/bc293f65-49f1-40be-93ae-931e91b40497">
<img width="337" alt="image" src="https://github.com/user-attachments/assets/dcccf9ad-fcbc-4f65-9742-98ee2c8d1882">
<img width="265" alt="image" src="https://github.com/user-attachments/assets/b6cff477-9718-4d42-8774-fcf094812b1a">
        
### A card visual was used to represent count of customers.




        
