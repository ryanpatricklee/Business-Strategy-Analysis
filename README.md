# SQL: Business Strategy Analysis
Utilized SQL and Tableaufor in-depth analysis of a company's growth prospects and performance.

[Link to the Tableau Storyboard](https://public.tableau.com/app/profile/ryan.lee1243/viz/DVDRentalAnalysisStoryboard/RockbusterPresentation)

## Project Objective
This project aims to understand the potential of the customer base of the analyzed business. By analyzing the data, the project answers the main business questions outlined by the management, analyzes the tastes and preferences of the customers, and determines whether they can be satisfied by the existing inventory.

### Key Questions:
- Which movies contributed the most and least to revenue gain?
- What was the average rental duration for all videos?
- Which countries are Rockbuster customers based in?
- Where are customers with a high lifetime value based?
- Do sales figures vary between geographic regions?
- What movie genres are most popular in the countries with the highest sales?
- Does the inventory match the customer interests in the top 10 countries? Are the most popular genres well represented?
- What genres do our top customers prefer?

### SQL Queries:
1. [List of all movies, including title, length, rental duration, rental rate, rating, genre, quantity on hand, number of rentals, and total revenue](https://github.com/ryanpatricklee/Business-Strategy-Analysis/blob/main/SQL%20Code/Movie%20info%20with%20total%20revenue)
2. [Customer count, total payment, and average amount paid in each country](https://github.com/ryanpatricklee/Business-Strategy-Analysis/blob/main/SQL%20Code/Customer%20count%20with%20payments)
3. [Top 10 customers: name, location, number of rentals, total money spent, ranked by money spent](https://github.com/ryanpatricklee/Business-Strategy-Analysis/blob/main/SQL%20Code/Top%2010%20customers)
4. [Genres rented by the top 10 customers](https://github.com/ryanpatricklee/Business-Strategy-Analysis/blob/main/SQL%20Code/Genres%20rented%20by%20top%20customers)
5. [Total number of rentals and revenue of each genre with a particular MPAA rating by country](https://github.com/ryanpatricklee/Business-Strategy-Analysis/blob/main/SQL%20Code/Genre%20rentals%20with%20total%20revenue)

   
In this data analytics project, I use PostgreSQL in conjunction with Tableau to answer business questions for a fictitious DVD rental company, Rockbuster Stealth, in service of applying my data analytics skills learned from [CareerFoundry](https://careerfoundry.com/). This repository contains the following:
- Project brief, fabricated for the purpose of learning
- Data dictionary
- SQL queries to answer business questions
- An entity relationship diagram (ERD) made with [DbVisualizer](https://www.dbvis.com/)

## Data
The DVD rental database represents the business processes of a DVD rental store. Descriptions and Entity Relationship Diagram can be found in the Data Dictionary file.
Here is the link to the [PostgreSQL DVD Rental sample database](https://www.postgresqltutorial.com/wp-content/uploads/2019/05/dvdrental.zip).
