# Movies ETL
## Overview of the Movies ETL Project:
In this project, Amazing Prime Video wants to predict the popularity of low budget movies for them to buy into for their streaming platform by sponsoring a Hackathon. They have identified Wikipedia and MovieLens websites for the ETL process.  

## Results:
In order to automate the ETL process, we created one function to *extract* all three files ([wikipedia.movies.json](wikipedia.movies.json), [ratings.csv](ratings.csv), [movies_metadata.csv](movies_metadata.csv)), *transform* the datasets by cleaning up bad data and joining the files together and *load* the clean dataset into PostgreSQL database.