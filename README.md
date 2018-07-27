# hawk-eye

# Introduction
 The project extracts data from GDELT global events datastore and analyses on the trending topics by country in a given timeframe. GDELT is a spatio temporal dataset with data from world's people, organizations, locations, themes and emotions which creates single holistic network over the entire planet.  


## Data Source
    GDELT website

    
## Architecture:
   Planning to create stream pipeline where new events from Kafka would stream through Spark streaming and will be loaded to      MySQL and Cassandra. The real time data request from Flask would fetch the data from MySQL and time series data from          Cassandra.

   Stream Pipeline:
   
   ## Kafka --> Spark Streaming --> (MySQL + Cassandra) --> Flask
                                









