# MongoDbCheatSheet2023
All you need to know about MongoDB.
## MongoDB Cheat Sheet

- Create and account or Login into https://www.mongodb.com/pricing#mdb-modal-shared.
- Best for small/Learning/Test projects.
- Choose your best cloud service provider; 
    - Aws.
    - GCP(Google Cloud Platform).
    - Azure.
- Select Location (eastus2).
- Create Cluster.

### 5 simple Steps to Getting Started.

- Create the Cluster.
- Create the Database User.
- Add a IP address of your Computer(Whitelist an IP) / Make your Cluster accessible from anywhere.
- Load Sample data or create the data Manually.
- Connect to your Mongo cluster.

### Authorization / Authentication.
- Username and password or Certificate.

#### Checking Mongo Version: .
- `db.version()`

#### Connect to MongoDB: .
- `mongo`

#### Show all databases: .
- `show dbs`

#### Use a database: .
- `use <db_name>`

#### Show all collections in a database: .
- `show collections`

#### Create a collection: .
- `db.createCollection("collection_name")`

#### Insert a document into a collection: .
- `db.collection_name.insert({field1: "value1", field2: "value2"})`

#### Find all documents in a collection: .
- `db.collection_name.find()`

#### Find documents with a specific condition: .
- `db.collection_name.find({field: "value"})`

#### Update a document in a collection: .
- `db.collection_name.update({field1: "value1"}, {$set: {field2: "new_value"}})`

#### Delete a document in a collection: .
- `db.collection_name.remove({field: "value"})`

### Insert Documents
#### Insert a single document: .
- `db.collection_name.insertOne({field1: "value1", field2: "value2"})`

#### Insert multiple documents in a collection: .
- `db.collection_name.insertMany([
   {field1: "value1", field2: "value2"},
   {field1: "value3", field2: "value4"},
   {field1: "value5", field2: "value6"}
])`

#### Find All Documents: .
- `db.collection_name.find()`

#### 




