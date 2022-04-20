# Big-Data - Project-1
# Application Title - CraigslistAnalyzer_USAUsedCarsbyOwner

## Project Description

CraigslistAnalyzer_USAUsedCarsbyOwner is a Scala application that cleans, proccesses and analyszes data using Apache Spark and Hive Distributed File System. It processes .csv files ontaining "Used Car - by Owner" data from every Craigslist Site in the United States of America, generated by means of custom web scrape implemented with Octaparse.

Data is cleaned to correct errors remove null data, and loaded into Spark Dataframes.

The available queries are:

[1]. Refresh Dataframes - Read data into dataframes from cleaned .csv data files.
[2]. Average Year of Car Made by Brand
[3]. Average Price for Car of X year
[4]. View counts of car brands for sale
[5]. Calculate percent of Posts that have images

<img src="https://github.com/brianvegh/CraigslistAnalyzer_USAUsedCarsbyOwner/blob/main/images/Octoparse2.png" width="100" height="100">

<img src="https://github.com/brianvegh/CraigslistAnalyzer_USAUsedCarsbyOwner/blob/main/images/Octoparse2.png">