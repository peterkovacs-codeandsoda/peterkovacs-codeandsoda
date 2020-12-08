# Redis, Lettuce & Spring Data Redis Integration

## 1. NoSQL
- relational databases are so 90s - engineered for another scenario both HW & SW
- data storage demand increased significantly in the last two decades
- relational databases are not perfect for the data partitioning


### 1.1. Scalability - CAP Theorem
1. C - Consistency
2. A - Availability
3. P - Partition Tolerance

### 1.2. Pick Two Rule
- CA - <span style="color:olive">relational databases</span>
- AP - <span style="color:steelblue">Dynamo</span>, <span style="color:seagreen">Cassandra</span>, <span style="color:maroon">SimpleDB</span>
- CP - <span style="color:steelblue">Redis</span>, <span style="color:seagreen">BigTable</span>, <span style="color:maroon">MongoDB</span>

### 1.3. Data Store Types
- <span style="color:steelblue">Key-Value</span>
- <span style="color:maroon">Document-Oriented</span>
- <span style="color:seagreen">Column-Oriented/Tabular</span>
- <span style="color:olive">Relational</span>


## 2. Redis
- one of the most commonly used
- key-value store(string, string)
- not just another key-value store(list,set,sortedset,hash,stream,etc)
- key expiration
- atomic operations:
  - GET, SET
  - LPOP, RPUSH
  - LRANGE
- high-availability and sharding:
  - standalone upstream/replica (startup topology refresh)
  - upstream/replica with Sentinel (runtime topology refresh)
  - static upstream/replica (topology refresh is off)
  - cluster mode (sharding nodes, periodical/adaptive topology refresh)

## 3. Lettuce
- standard Redis client
  - [Jedis](https://github.com/redis/jedis) is an alternative
- scalable, thread-safe
- based on [netty](http://netty.io/) and [Project Reactor](https://projectreactor.io/)
- synchronous API
- asynchronous API
- reactive API :+1:

## 4. Spring Data Redis Integration
- provides a common adapter based on Redis over the client implementations
- mainly used beans:
  - ConnectionFactory - LettuceConnectionFactory
  - RedisTemplate
  - RedisCacheManager
  - RedisCache
