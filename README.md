# Web-Scraping-with-Python
## Global data for Corona Virus

## Project overview
The project is about corona virus around the globe.  
I wrote some cool python code to accces the data from https://coronavirus.jhu.edu/data/mortality .   
Stored the data in DB Browser (SQLite) and then I imported them in Tableau to make a nice Viz!

Tools: Python,SQlite,Tableau,Atom

## Python Coding
Libraries used: BeautifoulSoup,Re,Urllib,Sqlite.       
Ok, so I used urllib to connect with the site and Beautifulsoup to parse the html and target the tags
containing the information. Then, I used Regular Expression to extract the strings inside the tags. Finally,
I used sqlite lib and wrote some code to create SQL tables and a for loop to insert the data in SQLite. The 
programm called 'corona.py'. You can access it **[here](https://github.com/DimKaisaris/Web-Scraping-with-Python/tree/main/Python%20Code)**
In this folder there is some other python code i wrote during the process which is part of corona.py , as well the sqlite files and an exported .csv  
used to connect with tableau.

## SQLite
The data was last updated at 19/1/2022. Take a look at the result as created automatic in Sqlite after I ran my python code!

![shot35](images/Screenshot35.png)


