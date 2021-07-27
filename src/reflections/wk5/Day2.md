# MongoDb Relationships (Day 2)


## What are the three types of relationships? 
The three types of relationships in MongoDb are One-To-One (1:1), One-To-Many (1:N), and Many-To-Many (N:M).


## What are the benefits of the traditional linking of relationships instead of Embedding
One of the benefits of traditional linking of relationships instead of embedding is that additional changes won't grow the original document, making it less likely that the application will run in the maximum document size of 16 MB. Another benefit is that it becomes easier to return information. 
## What are some of the challenges faced when deciding how to manage a many-to-many relationship that ultimately drive your decision on how to create it?
Well, some of the challenges with deciding how to manage a many-to-many relationship involve figuring out how many of one relationship there is compared to another. For instance, there might be a relationship where N is only a few while the ammount of M could be significantly larger, and in that instance you'd want to use one Way Embedding. So the relativity of values is an important factor, as well as what type of data you are going to be retrieving from the server. 

## Afternoon Challenge 
https://github.com/TimothyKimble/GregslistFullStack