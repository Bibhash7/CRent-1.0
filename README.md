# CRent-1.0
This is a Multi Database desktop based car rental application. MS-SQL Server is used for storing the transactional data where Cassandra No-SQL is used for storing and Analytics Purpose.

1. **Reason for MS SQL Server**: 
     a. For transactional data store as it provides more consistancy and availability.
2. **Reason for choosing Cassandra as data store**:
      a. Highly Available: Due to Cassandra's multi master architecture, the data is highly available.
      b. Columner Storage: Due to columner storage, aggregate operations works faster.
      c. No-SQL Database: Flexiblity.
            
## Release 1 DFD:
[![CRent-DFD-Image.png](https://i.postimg.cc/xjB1NPPh/CRent-DFD-Image.png)](https://postimg.cc/w3cpSLZQ)
