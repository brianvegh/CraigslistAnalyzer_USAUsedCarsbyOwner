# CraigslistAnalyzer_USAUsedCarsbyOwner
Craigslist analyzer that scrapes all used car by owner postings from every Craigslist site in the USA (420 sites), formats results, uploads to Hadoop HDFS and runs analytics with Spark dataframes to produce the following: 

  Brands for sale; 
  Percentage of postings that contain images; 
  Average prices by year, date and brand. 
  
Utilizes mySQL database to support user creation, login and access level, as well as log all user access attempts.
