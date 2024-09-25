# nosql-challenge

**This Module Includes:**

* [ ] The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. You've been contracted by the editors of a food magazine, Eat Safe, Love, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles.

**Part 1: Database and Jupyter Notebook Set Up**

1. The data provided in the establishments.json file is imported from  Terminal. Name the database uk_food and the collection establishments. Copy the text you used to import your data from your Terminal to a markdown cell in your notebook.
2. Within your notebook, import the libraries you need: PyMongo and Pretty Print (pprint).
3. Create an instance of the Mongo Client.
4. Confirm that you created the database and loaded the data properly: Confirm that uk_food is listed,ensure that establishments is there,document in the establishments collection using find_one and display with pprint.
5. assign the establishments' collection to a variable to prepare the collection for use

**Part 2: Update the Database**

1. Added the following information to the database that  new halal restaurant just opened in Greenwich.
2. Find the BusinessTypeID for "Restaurant/Cafe/Canteen" and return only the BusinessTypeID and BusinessType fields.
3. Update the new restaurant with the BusinessTypeID found.
4. checked how many documents contain the Dover Local Authority. Then, remove any establishments within the Dover Local Authority from the database, and ensure that how many Dover have been deleted.
5. some of the number values are stored as strings, when they should be stored as numbers.

**Part 3: Exploratory Analysis**

1. RatingValue refers to the overall rating decided by the Food Authority and ranges from 1-5. The higher the value, the better the rating.
2. The scores for Hygiene, Structural, and ConfidenceInManagement work in reverse.
3. Use count_documents to display the number of documents contained in the result and use  the first document in the results using pprint, Convert the result to a Pandas DataFrame and  print the number of rows in the DataFrame.
4. points to solved were :Which establishments have a hygiene score equal to 20,Which establishments in London have a RatingValue greater than or equal to 4,What were the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours", How many establishments in each Local Authority area have a hygiene score of 0and  Sort the results from highest to lowest, and print out the top ten local authority areas.

* [ ] **Conclusion**

In this project, I evaluated food hygiene ratings data from the UK Food Standards Agency to help the magazine "Eat Safe, Love" focus on establishments of interest. The analysis involved updating and querying the database, as well as converting and standardizing data types. Key findings included identifying establishments with hygiene issues and pinpointing top-rated restaurants near a specific location. This comprehensive approach can guide future articles targeting food hygiene trends across different regions.

* [ ] References: Class Recordings :- Zoom cloud
