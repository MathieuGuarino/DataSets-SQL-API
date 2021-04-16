<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Link malaria sick people with number of doctors
*Mathieu Guarino*

*[Iron Hack, DataAnalyze & 14/04/2021]*

## Content
- [Project Description](#project-description)
- [Hypotheses / Questions](#hypotheses-/-questions)
- [Dataset](#dataset)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)

<a name="project-description"></a>

## Project Description
The Project goal is to link two sources of data to find a link between the number of people Sick of Malaria and the number of doctors in the continent. There will be usage of an API and CSV files as a Dataset. The cleaned data will be hosted on SQL Cloud in order to add data in the long run. This data will be merged and used with Pandas dataframe to analyze the data.


<a name="hypotheses-/-questions"></a>

## Hypotheses / Questions
Is the number of doctor the only link with the number of sick people ?

<a name="dataset"></a>

## Dataset
There is two data sources :
The Global Health Organisation API

Kaggle CSV files Dataset :


I accessed Kaggle by creating a account on the website to download the files. The GHO is open and I read the documentation of the GHO OData API.

I cleaned the data with pandas then uploaded it with mysql.connector on SQL Cloud. I then accessed merged data with mysql.connector and SQL Queries

[Dataset](https://www.kaggle.com/imdevskp/malaria-dataset) 
[GHO API](https://www.who.int/data/gho/info/gho-odata-api)

<a name="workflow"></a>

## Workflow
The first difficulty was to find data which can be linked on the topic of Health.
I found the GHO API which has data on doctors by country. The only problem was that the country information was using short names so I had to get the country full name with another request then clean the data.
The dataset has malaria information by country.
My first step was to get these data and clean them into dataframes ready to be transfered into two SQL tables.
My second step was to learn how tu use cloud SQL with python and I followed a tutorial and some documentation after creating a test account on Google.
The third step was to cast the data into the right format and create the SQL tables. I had problems with numpy datatype.
The last steps was getting merged data from the two tables into python dataframe then do some stats to show if the number of sick people is only linked with the number of doctors.

<a name="organization"></a>

## Organization
How did you organize yourself? Did you use any tools?

<a name="links"></a>

## Links
Include the links to your repository, slides and trello. Feel free to include any other links associated to your project. 

[Repository](https://github.com/screamzz/DataSets-SQL-API/)  
[Trello](https://trello.com/b/9HULHhAJ/iron-hack)  

