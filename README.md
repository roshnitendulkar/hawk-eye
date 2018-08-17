# hawk-eye

# Introduction

 The project extracts data from GDELT global events datastore and analyses on the trending topics by country in a given timeframe. GDELT is a spatio temporal dataset with data from world's people, organizations, locations, themes and emotions which creates single holistic network over the entire planet.  

  ![Architecture.](./images/data_pipeline.jpg)

## Data Processing:
 
 The event data is extracted from S3 datasource and cleansed. The data is transformed to apply business logic and loaded to Cassandra. The flask web layer servers the analytics to display important events and historical trends.






