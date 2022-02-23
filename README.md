# Mission to Mars

## Overview of the analysis

This project is dedicated to learn and practice the web scrapping process using Chrome Developer Tools, BeautifulSoup, Splinter, MongoDB, Flask.

Required tools and purpose:
- Chrome Developer Tools was used to identify the HTML components attached to the required data;
- BeautifulSoup and Splinter were used to automate a web browser and collect the data we've identified;
- Mongo was used to store the data;
- Flask was used to create a web application to display the data. 

For a project purpose it was a task to collect some information about Mars from different websites, store it in a database and create a web application to display results in a user-friendly way.

## Results

Original code was written in the Jupyter Notebook to check results of a scrapping. After that the code was exported and modified in a Python file - the script was cleaned with created functions. The scrapped data was stored in a MongoDB, and index.html was created to display all received information in a nice way. The webpage was customized using Bootstrap components.

## Summary

Since we collected different types of information - news articles, tables, pictures - a NoSQL database MongoDB was used to store final information without a specific structure.

Flask allows to create a web application using Python and then customize it with HTML and CSS.

Using Flask, a web application was created that scrapes new data and displays it after every click of a button. The webpage was also customized using Bootstrap components.