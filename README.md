# nosql-challenge
Data Analytics Course Module 12

# Task
Using datasets from the UK Food Standards Agency, I will evaluate some of the ratings. I will work from the hypothetical scenario that journalists and food critics would be able to use these evaluations to make decisions about which establishments to write about.

# Methodology
I will work in Jupyter Notebook and use MongoDB to import create the database, load data and create a collection. Using MongoDB functions, I'll perform CRUD operations on the collection. Finally, to answer a series of key questions about establishments, I'll use Pandas to create DataFrames.

## Part 1: Database and Jupyter Notebook Set Up
I imported all the data from the establishments.json file and created a **uk_food database** and a collection called **establishments** which I saved as a variable to use in future CRUD operations.

## Part 2: Update the Database
Using provided information, I added a new establishment to the establisments collection. I updated the BusinessTypeID for this new establishment, deleted all establishments located in the Dover Local Authority, and updated some datatypes.

## Part 3: Exploratory Analysis

1. **Question 1: Which establishments have a hygiene score equal to 20?**  There were 41 establishments with a hygiene score of 20. The first five were: 'The Chase Rest Home', 'Brenalwood', 'Melrose Hotel', 'Seaford Pizza', 'Golden Palace'. They were all located in Essex or East Sussex.
  
2. **Question 2: Which establishments in London havea RatingValue greater than or equal to 4?** There were 33 establishments with a RatingValue of 4 or more. The first five were: 'Charlie's', 'Mv City Cruises Erasmu', 'Benfleet Motor Yacht Club', 'Coombs Catering t/a The Lock and Key'. 'Tilbury Seafarers Centre'. The first three were a *BusinessType: Other catering premises* while the last two are *BusinessType: Restaurant/Cafe/Canteen*.
  
3. **Question 3: What are the top 5 establishments with a Rating Value of 5, sorted by lowest hygiene score, nearest to the new resturant added, "Penang Flavours?** The top 5 establishments that meet this criteria are 'Volunteer', 'Plumstead Manor Nursery', 'Atlantic Fish Bar', 'Iceland'. and 'Howe and Co Fish and Chips - Van 17'.
  
4. **Question 4: How many establishments in each Local Authority area have hygiene score of 0?** There are 55 different Local Authories. Here are the values for the first 10:
    - Thanet	1130
    - Greenwich	882
    - Maidstone	713
    - Newham	711
    - Swale	686
    - Chelmsford	680
    - Medway	672
    - Bexley	607
    - Southend-On-Sea	586
    - Tendring	542
