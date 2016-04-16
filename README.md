# Internet Terms

Commonly used but hard to understand web development + programming terms explained in simple english.

### <a name='dsl'></a>DSL(Domain Specific Language) 
A language that is meant to accomplish a specific task. Examples include: SQL, rake, make, XML, YAML, HTML, CSS. In contrast to GPL(General Programming Language)
Ruby is a popular choice to make DSLs.

### <a name='meta'></a>Meta 
Self referencing, e.g. metadata: data about data (author, filesize for a file can be considered metadata)
                  e.g. metacognition: thinking about thinking
                  
### <a name='rack'></a>Rack
Provides an interface(i.e. can communicate) between [webservers](#webservers) that support ruby(e.g. webrick) and ruby framework(e.g. ruby on rails) 

### <a name='webservers'></a>Webservers
Software that interprets HTTP, examples: Apache, WEBrick, NGINX

### <a name='serialization'></a>Serialization/Marshalling & Deserialization/Unmarshalling
Translating data structures(e.g. array) or [object](#object) states into a format that can be stored in memory or transmitted(e.g. over the internet). 

In contrast deserialization/unmarshalling is rereading data according to the serializaed format so as the produce an identical data structure or object state i.e. simply the opposite of serialization/marshalling. Put another way it is the extraction of the data structure.

Serialization formats include: YAML, JSON, XML

### <a name='object'></a>Object
In Computer Science - Examples include: variables, data stuctures(e.g. arrays) and functions 

In Object orientated programming - An instance of a class 

In relational databases - Table, column or association 

### <a name='semantics'></a>Semantics
Intended meaning/behaviour

### <a name='oauth'></a>OAuth 2.0
![webserverflow](http://farm2.staticflickr.com/1681/26295812091_4f233ffa01_b.jpg "webserverflow")

### <a name='ORM'></a>ORM(object relational mapping)
The heart of the problem is translating the logical representation of the objects into an atomized form that is capable of being stored in the database, while preserving the properties of the objects and their relationships so that they can be reloaded as objects when needed. If this storage and retrieval functionality is implemented, the objects are said to be persistent. Active record achieves this in rails. 

### <a name='nosql'></a>NoSQL(refers to "non-sql" or "non relational" but can also be "not only sql")
Examples: MongoDB, Cassandra, HBase, Neo4j. 
NoSQL compliements "big data" and agile development since data is not mapped in fixed tables and types, new types of data can be easily added. Where as in SQL db if a new attribute needs to be added to a table this can be costly because everything is fixed. Furthermore NoSQL is horizontally scalable vs SQL vertical scalable. Horizontal scalability is said to be better since it is easier to achieve and there is no upper bound. 
