## Redis, Lettuce & Spring Data Redis Integration

### NoSQL
- relational databases are so 90s - engineered for another scenario both HW & SW
- data storage demand increased significantly in the last two decades
- relational databases are not perfect for the data partitioning
```markdown
**Scalability - CAP Theorem**
1. C - Consistency
2. A - Availability
3. P - Partition Tolerance

**Pick Two Rule**
- CA - <span style="color:olive">relational databases</span>
- AP - <span style="color:steelblue">Dynamo</span>, <span style="color:seagreen">Cassandra</span>, <span style="color:maroon">SimpleDB</span>
- *CP* - <span style="color:steelblue">Redis</span>, <span style="color:seagreen">BigTable</span>, <span style="color:maroon">MongoDB</span>

**Data Store Types**
- <span style="color:steelblue">Key-Value</span>
- <span style="color:maroon">Document-Oriented</span>
- <span style="color:seagreen">Column-Oriented/Tabular</span>
- <span style="color:olive">Relational</span>
```

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
