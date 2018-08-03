# hawk-eye

# Introduction
 The project extracts data from GDELT global events datastore and analyses on the trending topics by country in a given timeframe. GDELT is a spatio temporal dataset with data from world's people, organizations, locations, themes and emotions which creates single holistic network over the entire planet.  


## Data Source
    GDELT website

    
## Architecture:
   Planning to create batch pipeline where new events from S3 would process through Spark daily and will be loaded to      Cassandra. 

   Stream Pipeline:
   
   ## S3 --> Spark --> Cassandra --> Flask
                                









