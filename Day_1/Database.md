# Data Base Leason

how to configure
how to setup
how to manage
replication
backups
ewstore Db

## types of database

- Key Value Databases
    Redis , Memcached , etcd from Kubernetes  
keys  value
3245  "name": "Mike"  unique keys and no joins

the store data in memory : very fast
u can't use for primary storage

Best for:
    caching
    message queue
but it use along another db to make stuff faster

- Wide Column Database
    Cassandra   HBase
stores unstructed data with dynamic numbers of keys there are schema-less

      Row key      column   column

Row -->  mike       name      age
                    mike       21
it scalabe no joins
has similar query to sql
Best for:
    Time series, iot-records , sensors
the should be use unto of a primary data of Historical event

- Document Database
    Mongodb, DynamoDb, couchDb
there are use for implentation of data in document form
Document         Document
"name":"mike"    "color": "blue"
"age": 29         "size": "100cm"
The are also schema-less
no joins
denormalized
Best For:
    Mobile apps
    gane apps
    cms
    most  apps
it could be use as a primary data base for the application
fast to read , easy to get started, primary

- Relational Databases
    Mysql , Postgresql
they are most use and it is structured data base
they store structured data
schema and data types needs to be created first
it query language(sql) ==> Structured Query Language(sql)
it use rows and columns
ACID: Atomicity, Consistency, Isolation, Durability
it is normalized datatbase
it is dificult to scale

cockroach db is design to solve scalability issues

- Graph Database
    Neo4j Dgraph
Best for:
    Graphs
    patterns
    recommendation

- Search Databases
    ElasticSearch , Solr
search Database through massive data entries
full text search in efficent and fast way
Similar to document -orientated database
