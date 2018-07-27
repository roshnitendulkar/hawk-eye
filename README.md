# hawk-eye

# Introduction
 The project extracts data from GDELT global events datastore and analyses on what are the trending topics by country in almost real time. GDELT is a spatio temporal dataset with data from world's people, organizations, locations, themes and emotions which creates single holistic network over the entire planet.  


## Data Source

### Batch Data :
    https://registry.opendata.aws/gdelt/
     
### Streaming Data :
    GDELT uploads the dataset every 15 minutes at the below location. 
    http://data.gdeltproject.org/gdeltv2/lastupdate.txt    

    
## Data Architecture:
   Planning to create batch and streaming data

   Batch Pipeline:
   S3 --> Spark Streaming --> Cassandra

   Stream Pipeline:
   Kafka --> Spark Streaming --> Cassandra -->Flask









