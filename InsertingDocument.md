### This file contains a list of all the methods that can be used to insert a document in a collection

+ **`db.collection_name.insertOne({})`** -> adds a single document in the collection <collection_name>. If the collection does not exist, it also creates the collection.
+ **`db.collection_name.insertMany([{},{},{}])`** -> adds an array of documents in the collection <collection_name>. If the collection does not exist, it also creates the collection.
+ In addition functions like `updateOne()`, `updateMany()`, `findOneAndUpdate()`, `findOneAndReplace()`, `findAndModify()` can also insert a document if the upsert flag is true.
