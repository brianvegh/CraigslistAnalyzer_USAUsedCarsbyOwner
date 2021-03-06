# Big-Data - Project-1
# Application Title - CraigslistAnalyzer_USAUsedCarsbyOwner

## Project Description

CraigslistAnalyzer_USAUsedCarsbyOwner is a Scala application that cleans, processes and analyzes data using Apache Spark and Hive Distributed File System. It processes .csv files containing "Used Car - by Owner" data from every Craigslist Site in the United States of America, generated by means of custom web scrape implemented with Octoparse. Data is cleaned to correct errors remove null data, and loaded into Spark Dataframes.

<img src="https://github.com/brianvegh/CraigslistAnalyzer_USAUsedCarsbyOwner/blob/main/images/Octoparse2.png">

<img src="https://github.com/brianvegh/CraigslistAnalyzer_USAUsedCarsbyOwner/blob/main/images/Octoparse0.png">


The available queries are:

1. Refresh Dataframes - Read data into dataframes from cleaned .csv data files.
2. Average Year of Car Made by Brand
3. Average Price for Car of X year
4. View counts of car brands for sale
5. Calculate percent of Posts that have images

## Technologies Used

- Scala 2.12.10
- Apache Spark 3.1.2
- MySQL 8.0.28
- Hadoop 3.3.0
- Hive 3.1.2
- OpenJDK 8
- Octoparse
- SHA-512
- IntelliJ IDEA 2020.2.3
- MySQL Workbench 8.0.28
- Ubuntu 18.0.4

## Features

- User encrypted password using SHA-512
- User management restricts functionality and access according to user level (Admin, Basic), persisted in SQL
- Logs user account logins as failures or successes, as well as password updates. These logs are visible to Admin users from within the app.
- Queries results in .csv files
- Users can input parameters on queries
- Prints results to .csv file

### To-do list:

- Implement JSON output file writer
- Persist data to spark warehouse after application close

## Getting Started

- Clone the repository

        _git clone https://github.com/brianvegh/CraigslistAnalyzer_USAUsedCarsbyOwner_

- Install the required software within technologies used list 

- Configure HDFS access through localhost:9000 port(or change this value in the main object for the desired value)
- Create an user in MySQL who can access Craigslist database and its tables.
- Open Intellij and run object CraigslistAnalyzer

## Usage

Bellow are listed some APP's screenshots.

<img src="https://github.com/brianvegh/CraigslistAnalyzer_USAUsedCarsbyOwner/blob/main/images/1.png">

<img src="https://github.com/brianvegh/CraigslistAnalyzer_USAUsedCarsbyOwner/blob/main/images/1.png">

<img src="https://github.com/brianvegh/CraigslistAnalyzer_USAUsedCarsbyOwner/blob/main/images/2.png">

<img src="https://github.com/brianvegh/CraigslistAnalyzer_USAUsedCarsbyOwner/blob/main/images/3.png">

<img src="https://github.com/brianvegh/CraigslistAnalyzer_USAUsedCarsbyOwner/blob/main/images/4.png">

<img src="https://github.com/brianvegh/CraigslistAnalyzer_USAUsedCarsbyOwner/blob/main/images/5.png">

<img src="https://github.com/brianvegh/CraigslistAnalyzer_USAUsedCarsbyOwner/blob/main/images/6.png">

<img src="https://github.com/brianvegh/CraigslistAnalyzer_USAUsedCarsbyOwner/blob/main/images/7.png">

<img src="https://github.com/brianvegh/CraigslistAnalyzer_USAUsedCarsbyOwner/blob/main/images/Octoparse1.png">
