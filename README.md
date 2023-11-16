NoSQL Challenge: UK Food Standards Agency Data Analysis

This repository encompasses code and data for the NoSQL Challenge, focusing on the analysis of food hygiene ratings data collected by the UK Food Standards Agency. The objective is to provide insights aiding the food magazine "Eat Safe, Love" in making informed decisions about future article topics.

Part 1: Database and Jupyter Notebook Setup

Configure the database and Jupyter Notebook environment, involving the following key steps:

Import data from "establishments.json" into a MongoDB database named "uk_food," creating a collection named "establishments."
List databases in MongoDB, confirming the presence of "uk_food."
Confirm the existence of the "establishments" collection and display a sample document.
Import necessary libraries like PyMongo and Pretty Print (pprint).
Part 2: Database Update

The editorial team at "Eat Safe, Love" has specific requirements for the database. Perform the following tasks:

Add a new halal restaurant, "Penang Flavours," to the database.
Find the BusinessTypeID for "Restaurant/Cafe/Canteen" and update "Penang Flavours" with the correct BusinessTypeID.
Remove all establishments in the "Dover Local Authority."
Update number values from strings to numeric types using update_many.
Part 3: Exploratory Analysis

This section involves answering specific questions to assist the magazine editors in making data-driven decisions. The analysis includes:

Identify establishments with a hygiene score of 20.
Locate establishments in London with a RatingValue greater than or equal to 4.
Find the top 5 establishments with a RatingValue of 5, sorted by the lowest hygiene score and proximity to "Penang Flavours."
Determine the number of establishments in each Local Authority area with a hygiene score of 0, sorting the results, and listing the top ten local authority areas.




