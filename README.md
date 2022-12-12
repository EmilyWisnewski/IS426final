IS426 Final Project - Forbes Billionaires

My name is Emily Wisnewski and this is my project for IS426.  I decided to focus on webscraping and running MySQL on the databased formed specifically for this project.  

This project is intended to webscrape data from the Forbes list of richest people in the world, and read it in while putting it into an SQL database that is created.  After the data is loaded into SQL, the user will be able to run queries to answer various questions they mave have about the data. The inital data can be found in a JSON format and iterated through naturally by indexing to the particular columns the user wants to be included in the table.  I faced some challenges due to null or repeating values of the primary key, so I had to add many exceptions and a try to avoid the program stopping every time and error occured.  

This should ideally be run in Jupyter Notebook and PyMySQL.  This will allow the user to upload data to the database and use MySQL to run queries on the data.  

When this data is loaded and the code is ran, there will be many errors, but that is becasue the data already exists in the database.  For no errors, just delete the data in MySQL while keeping the schema so the code can repopulate the database. 



