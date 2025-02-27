# nosql-challenge

For this challenge I have been contracted by the editors of a food magazine, Eat Safe, Love, to analyse and evaluate restaurant ratings. The main objective is to extract valuable insights from data on establishments across various locations, focusing on hygiene scores and geographical factors.

The code is split up into 3 parts: 
-Database & Jupyter Notebook Set UP
-Update the Database
-Exploratory Analysis

Part 1: Database Setup

In the section I imported the data from the given JSON file into a MongoDB database. Afterwards, the necessary libaries such as PyMongo to interact with the database. A MongoCLient was created to establsih the connection. Next, I verified the connection was establish and the database was created. Afterwards, I assigned the database to a variable name and reviewed our collection and finally assigned a variable to the collection. Establishing a verifying these connections are created will help in our further analysis and queries of the database. 

Part2: Updating the Database with Modifications

In this section, I updated the database to add a new restaurant Penang Flavours, which is located in Greenwich but has not yet been rated. Fields that were added for this new establishment were business name, type, location, and more. As well assigning the correct  BusinessTypeID and BusinessType for the new establishment. Afterwards, all establishments in Dover were than removed because the maganize is not interested in them.

Part3: Exploratory Analysis

In this section, I analyzed the data to answer certain questions that the magazine company wanted to know about. 

1. Which establishments have a hygiene score equal to 20?
   41 establishments had a score equal to 20

2. Which establishments in London have a RatingValue greater than or equal to 4?
   0 establishments

3. What are the top 5 establishments with a RatingValue rating value of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
   results are in the code

4. How many establishments in each Local Authority area have a hygiene score of 0?
   results are in the code

Conculsion:

By completing this task, it demonstrates how MongoDB can be useful in organizing, updating and analyzing large datasets. This can aid with big companies such as the magazine company to take queries, sort and filter info to gain insight and knowledge of certain establisments in the area. This data can than be used by the company to help in decision making. 

