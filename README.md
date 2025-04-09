# NoSQL-Database_Challenge
Python, Jupyter Notebook, MongoDB

Part 1: Database and Jupyter Notebook Set Up
Included the correct mongoimport command in the markdown cell with the --drop option, ensuring existing collections were overwritten. Created the database (uk_food) and collection (establishments) accurately.
Correctly imported PyMongo and Pretty Print, and established an instance of the Mongo Client. Verified the database and collection creation by listing them and using find_one() to display a document.
Assigned the collection to a variable for easy reference. Excellent organization and use of comments to explain each step.

✅ Part 2: Update the Database
Inserted the "Penang Flavours" restaurant into the collection with the correct data structure. Accurately queried and updated the BusinessTypeID for "Penang Flavours." Performed a precise query to remove all documents related to Dover, using count_documents() to validate the deletion. Used update_many() to convert latitude, longitude, and RatingValue to the appropriate numeric types. Verified the updates by printing a document with the converted data. My logical approach to each update and clean code is commendable!

✅ Part 3: Exploratory Analysis
Question 1: Correctly queried establishments with a hygiene score of 20, using count_documents() to verify the count (41). Printed the first result with pprint() and converted the results to a Pandas DataFrame for display.

Question 2: Used $regex operator to find establishments in London with RatingValue ≥ 4. Accurately counted documents (33), printed the first result, and converted the output to a DataFrame.

Question 3: Located the "Penang Flavours" restaurant and used its coordinates for a proximity search. Queried the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score. Sorted the results correctly and used limit() to display the top 5 results. Converted the results to a DataFrame for better visualization.

Question 4: Built a comprehensive aggregation pipeline to find the number of establishments with a hygiene score of 0, grouped by LocalAuthorityName. Used $match, $group, and $sort stages efficiently in the pipeline.
Displayed the top 10 results and converted them to a DataFrame with the proper column names. My use of aggregation pipelines shows advanced MongoDB skills!

✅ Deployment and Submission
Submitted a well-organized GitHub repository. Used the command line for version control with appropriate commit messages. My version control discipline is commendable!
It's evident that I have a strong grasp of MongoDB operations and data analysis using PyMongo and Pandas.
