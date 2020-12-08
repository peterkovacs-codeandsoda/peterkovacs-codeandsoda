## Redis, Lettuce & Spring Data Redis Integration

### NoSQL
- relational databases are so 90s - engineered for another scenario both HW & SW
- data storage demand increased significantly in the last two decades
- relational databases are not perfect for the data partitioning

**Scalability - CAP Theorem**
1. C - Consistency
2. A - Availability
3. P - Partition Tolerance

**Pick two**
- CA - <span style="color:grey">relational databases</span>
- AP - <span style="color:steelblue">Dynamo</span>, <span style="color:grass">Cassandra</span>, <span style="color:aqua">SimpleDB</span>
- *CP* - <span style="color:aqua">MongoDB</span>, <span style="color:grass">BigTable</span>, <span style="color:steelblue">**Redis**</span>

**Store Types**
- <span style="steelblue">Key-Value</span>
- <span style="aqua">Document-Oriented</span>
- <span style="grass">Column-Oriented/Tabular</span>
- <span style="grey">Relational</span>

### Redis
- one of the most commonly used
- key-value store(string, string)
- not just another key-value store(list,set,sortedset,hash,stream,etc)
- key expiration
- atomic operations
-- GET
-- SET
-- LPOP
-- RPUSH
-- LRANGE

### Lettuce


### Spring Data Redis Integration
