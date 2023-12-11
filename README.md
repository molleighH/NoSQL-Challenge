# NoSQL-Challenge
### Module 12 Homework 

<img align="right" width="250" height="150" src="https://github.com/molleighH/NoSQL-Challenge/blob/main/uk%20food%20standards%20agency.jpeg?raw=true">

<samp>The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. You've been contracted by the editors of a food magazine, Eat Safe, Love, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles.</samp>


## Part 1: Database and Jupyter Notebook Set Up

##### Use NoSQL_setup_starter.ipynb for this section of the challenge.
    
* Import the data provided in the establishments.json file from your Terminal. 
    * Name the database uk_food and the collection establishments. 
    * Copy the text you used to import your data from your Terminal to a markdown cell in your notebook.

* Within your notebook, import the libraries you need: PyMongo and Pretty Print (pprint).

* Create an instance of the Mongo Client.

* Confirm that you created the database and loaded the data properly:

    * List the databases you have in MongoDB. Confirm that uk_food is listed.
    * List the collection(s) in the database to ensure that establishments is there.
    * Find and display one document in the establishments collection using find_one and display with pprint.
    
* Assign the establishments collection to a variable to prepare the collection for use.

## Part 2: Update the Database

##### Use NoSQL_setup_starter.ipynb for this section of the challenge.

The magazine editors have some requested modifications for the database before you can perform any queries or analysis for them. Make the following changes to the establishments collection:

<img align="right" width="250" height="300" src="https://github.com/molleighH/NoSQL-Challenge/blob/main/Screenshot%202023-12-10%20at%207.43.52%20PM.png?raw=true">

* An exciting new halal restaurant just opened in Greenwich, but hasn't been rated yet. The magazine has asked you to include it in your analysis. Add the following information to the database:
