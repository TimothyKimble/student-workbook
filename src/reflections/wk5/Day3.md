# MongoDb Relationships (Day 3)


## In simple terms what is a sub-document?
In Mongoose, subdocuments are documents that are nested inside other documents. Another term for subdocuments is embedded documents. 
## When might you use a sub-document?
You might want to use a sub-document when you want to create something that can be changed or modified. For instance if you were building a video game with multiple characters, you could use a sub-document to list their moves, and easily change their moves if you wanted to add or take away from them. 
## How do you add to a collection of sub-documents? What about editing them?
You can create a new subdocument using the parameters set in the collection. After creating a new document, you can edit the property values by accessing the same models collection of parameters, and change them by saving the document 