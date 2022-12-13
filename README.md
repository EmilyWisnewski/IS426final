IS426 Final Project - Forbes Billionaires

My name is Emily Wisnewski and this is my project for IS426.  I decided to focus on webscraping and running MySQL on the databased formed specifically for this project.  

![Alt text](/images/pic1.png "Data Source")

The data source used is screenshotted above, and is retreieved from https://www.forbes.com/billionaires/ .  This list includes many peices of data about the richest people in the world.  This intrigued me becasue I have always found it interesting to look into that 1% and see what companies or circumstances made them that successful.  

![Alt text](/images/picdata.png "Data in SQL")

![Alt text](/images/picschema.png "Schema SQL")

Above, are the photos that display the data and schema retreieved from SQL.  The schema is created of several important peices of information from the JSON data.  This includes name, age, country, organization, industries, gender, rank, final worth, net worth, and title.  These felt like the most important columns to include to portray the full picture the user would need to see.  The relation to the JSON viewer can be seen below with the pictures of the JSON viewer.  The related columns in the JSON data are personName, age, country, organization, industries, gender, rank, finalWorth, and netWorth, and title.  

![Alt text](/images/pic2.png "Json Viewer")

![Alt text](/images/pic3.png "Json Viewer")

![Alt text](/images/pic4.png "Json Viewer")

The goal of this database is for users to sort through the data and run queries on any questions they may have.  An example query can be seen below!

![Alt text](/images/picquery.png "SQL Query")


This project is intended to webscrape data from the Forbes list of richest people in the world, and read it in while putting it into an SQL database that is created.  After the data is loaded into SQL, the user will be able to run queries to answer various questions they mave have about the data. The inital data can be found in a JSON format and iterated through naturally by indexing to the particular columns the user wants to be included in the table.  I faced some challenges due to null or repeating values of the primary key, so I had to add many exceptions and a try to avoid the program stopping every time and error occured.  An auto increment primary key called id was added in order to avoid the data from throwing errors.  This id is not relevant to the queries being run.  

This should ideally be run in Jupyter Notebook and PyMySQL.  This will allow the user to upload data to the database and use MySQL to run queries on the data.  




