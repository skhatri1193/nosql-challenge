
# NoSQL Challenge: UK Food Hygiene Ratings

## Project Overview

This project involves working with data from the UK Food Standards Agency, which evaluates food establishments across the United Kingdom. The data will be stored in a MongoDB database and analyzed using PyMongo. The aim is to provide insights for a food magazine,  *Eat Safe, Love* , to help journalists and food critics decide which establishments to visit and write about.

## Project Structure

* **Part 1: Database and Jupyter Notebook Set Up**
  The project begins by setting up a MongoDB database and importing data from an `establishments.json` file into a collection named `establishments`. This step includes confirming the database and collection setup.
* **Part 2: Update the Database**
  Several modifications are made to the data:
  * A new restaurant, "Penang Flavours," is added to the database.
  * Establishments from Dover are removed.
  * Data types for certain fields (latitude, longitude, and RatingValue) are converted to their appropriate types.
* **Part 3: Exploratory Data Analysis**
  Using MongoDB queries and aggregation, we analyze the dataset to answer specific questions such as:
  * Establishments with a hygiene score equal to 20.
  * London establishments with a RatingValue of 4 or higher.
  * The top 5 establishments with a RatingValue of 5, sorted by hygiene score, nearest to "Penang Flavours."
  * Local authorities with the highest number of establishments having a hygiene score of 0.

## Technologies Used

* **MongoDB** : A NoSQL database used to store and manage the dataset.
* **PyMongo** : A Python library for interacting with MongoDB.
* **Pandas** : A Python library used for data manipulation and analysis.
