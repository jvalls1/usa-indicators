## Data Modeling

### Criteria

Data model is based on the possible actions and queries of users. It has two main advantges doing this way:
* Costly queries will be limited, avoiding the myth of 50.000 $ query on a cloud platform
* The use of guided and well known concepts provided to users increases the utility of platform.

Another criteria that must conform the design is the possibility of increase or add new datasets
not initially provided by this project to be out of scope. The open data policy of goverment let us to
add all kind of interesting data. 

### Models

A separation between logic model and physical model will be undertake, because the initial intention 
was to deploy the data in various platforms. Initial interests are:

* Local Postgress, to make a proof of concept before deploy at Cloud Platform
* Cloud Plaform, AWS is choosen, due to course continuity and knowledge.
* Snowflake to proof a commerical platform with the promise of simplifing data engeniering. 

