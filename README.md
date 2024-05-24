# NoSQL Challenge and Data Analysis Project

## Project Overview

This project involves setting up a NoSQL database, updating it with specific requirements, and performing exploratory data analysis on food hygiene ratings in the UK. The data is provided by the UK Food Standards Agency, and the analysis will help the editors of a food magazine, Eat Safe, Love, decide where to focus future articles.

## Deliverables

### Part 1: Database and Jupyter Notebook Setup

1. **Objective**: Set up the database and import data.
2. **Tools Used**: MongoDB, PyMongo, Pretty Print.
3. **Steps**:
   - Import `establishments.json` data into a MongoDB database named `uk_food` and a collection named `establishments`.
   - Verify the database and collection creation.
   - Assign the `establishments` collection to a variable for use.

### Part 2: Update the Database

1. **Objective**: Perform specific modifications to the database.
2. **Steps**:
   - Add a new restaurant "Penang Flavours" to the database.
   - Find and update the `BusinessTypeID` for "Restaurant/Cafe/Canteen".
   - Remove establishments located in Dover.
   - Convert `latitude`, `longitude`, and `RatingValue` fields to appropriate numeric data types.

### Part 3: Exploratory Analysis

1. **Objective**: Answer specific questions using the database.
2. **Tools Used**: PyMongo, Pandas.
3. **Questions**:
   - Find establishments with a hygiene score of 20.
   - Find establishments in London with a `RatingValue` greater than or equal to 4.
   - Identify the top 5 establishments with a `RatingValue` of 5, sorted by lowest hygiene score, nearest to "Penang Flavours".
   - Count the number of establishments in each Local Authority area with a hygiene score of 0 and list the top ten.

## Repository Structure

- `NoSQL_setup_starter.ipynb`: Jupyter Notebook for setting up and updating the database.
- `NoSQL_analysis_starter.ipynb`: Jupyter Notebook for performing the exploratory analysis.
- `establishments.json`: JSON file containing the initial dataset.

## Instructions

### Part 1: Database Setup

1. Open `NoSQL_setup_starter.ipynb`.
2. Use the provided `mongoimport` command to import the `establishments.json` file.
3. Verify the database and collection setup using PyMongo.

### Part 2: Update the Database

1. Add the "Penang Flavours" restaurant to the `establishments` collection.
2. Find and update the `BusinessTypeID` for "Restaurant/Cafe/Canteen".
3. Remove documents with the Local Authority "Dover".
4. Convert `latitude`, `longitude`, and `RatingValue` fields to numeric types.

### Part 3: Exploratory Analysis

1. Open `NoSQL_analysis_starter.ipynb`.
2. Perform queries to answer the specified questions.
3. Convert the query results to Pandas DataFrames for analysis and visualization.

## Submission

Submit the URL of your GitHub repository containing the Jupyter notebooks and any additional files for grading.

## References

- [UK Food Standards Agency](https://www.food.gov.uk/)

---

## Author

Kevin Ngala

© 2024 edX Boot Camps LLC
