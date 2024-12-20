# nosql-challenge
Data Analytics Course Module 12

# Task
Using datasets from the UK Food Standards Agency, I will evaluate some of the ratings. I will work with the hypothetical scenario that journalists and food critics would be able to use these evaluations to make decisions about which establishments to write about.

# Methodology
I will work in Jupyter Notebook and use MongoDB to import create the database, load data and create a collection. Using Mongo functions, I'll perform CRUD operations on the collection. Finally, to answer a series of key questions about establishments, I'll use Pandas to create DataFrames.

## Part 1:Database and Jupyter Notebook Set Up
I imported all the data from the establishments.json file and created a uk_food database and a collection called establishments which I saved as a variable to use in future CRUD operations.

## Part 2: Update the Database
Using provided information, I added a new establishment to the establisments collection. I updated the BusinessTypeID for this new establishment, deleted all establishments located in the Dover Local Authoirty, and updated some datatypes.

## Part 3: Exploratory Analysis

- **Question 1: Which establishments have a hygiene score equal to 20?**  
- **Question 2: Which establishments in London havea RatingValue greater than or equal to 4?**
- **Question 3: What are the top 5 establishments with a Rating Value of 5, sorted by lowest hygiene score, nearest to the new resturant added, "Penang Flavours?**    
- **Question 4: How many establishments in each Local Authority area hava hygiene score of 0?** 

    
    ![bar chart of sorted daily pressure on Mars](images/avg_pressure_monthly.png)
