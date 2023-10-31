# Digital-Music-Store-Data-Analysis

Data Analysis project to help **Chinook Digital Music Store** to help how they can optimize their business opportunities and to help answering business related questions.
In this project, you will query the Chinook Database. The Chinook Database holds information about a music store. For this project, you will be assisting the Chinook team with understanding the media in their store, their customers and employees, and their invoice information. To assist you in the queries ahead, the schema for the Chinook Database is provided below. You can see the columns that link tables together via the arrows

[schema credit to](https://github.com/lerocha/chinook-database/wiki/Chinook-Schema)
![schema](https://raw.githubusercontent.com/ptyadana/data-analysis-digital-music-store/master/ChinookSchema.png)

## Steps followed during projects:
1. ## Extract the dataset

https://github.com/lerocha/chinook-database/tree/master/ChinookDatabase/DataSources

2. ## Analyse the data (identify relations between different tables) ## DATA OVERVIEW
![image](https://github.com/gauraishwarya/Music-Store-Data-Analysis-Project-SQL/blob/main/schema_diagram.png?raw=true)

3. ## Cleansing of data:
   
 a) remove redundant data or incorrect data.
 
 b) Exclude data which is not required for your project.
 
 c) Fixing wrong data.
 
 d) etc etc.
 
4. ## Draw insights from data (solve problems or answers given questions using data / Visualize data to share with stakeholders.

1) Are there any albums owned by multiple artist?
2)  Is there any invoice which is issued to a non existing customer?
3)  Is there any invoice line for a non existing invoice?
4)  Are there albums without a title?

   -- SQL Queries to answer some questions from the chinook database.
1) Find the artist who has contributed with the maximum no of songs. Display the artist name and the no of albums.
2) Display the name, email id, country of all listeners who love Jazz, Rock and Pop music.
3) Find the employee who has supported the most no of customers. Display the employee name and designation
4) Which city corresponds to the best customers?
5) The highest number of invoices belongs to which country?
 


