Requirement for using MongoDB and Spark:
  1. Java >= 11 (sugguest java 11)
  2. Scala (sugguest scala 2)
  3. MongoDB (sugguest 4.4) 
  5. MongoDB-spark-connector, use can download here: https://www.mongodb.com/docs/spark-connector/master/
  6. Spark version >= 3 with Hadoop >= 2.7

In previous step, we've imported data from json file to MongoDB in database's name Data and collection data.
This step is loading data from MongoDB to Spark and using Spark to analyze students' performance.
You must check your MongoDB status & collection by going to MongoDB's local location and run this command:
```bash
mongo
show dbs
use Data
show collections
db.data.count()
```
If the result is the same with the picture below, you can use "ReadDataFromMongoDBtoSpark.ipynb" to get data
![Capture](https://user-images.githubusercontent.com/80337571/164374469-76ddc42d-8c26-4e7b-9c67-d73573faaf6a.PNG)


