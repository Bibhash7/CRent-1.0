# CRent-1.0
This is a Multi Database desktop based car rental application. MS-SQL Server is used for storing the transactional data where Cassandra No-SQL is used for storing and Analytics Purpose.

Upd: Added Triggers to store the deleted user and cars information into userlogs and carslogs respectively.

1. **Reason for choosing MS SQL Server**: 
     a. For transactional data store as it provides more consistancy and availability.
2. **Reason for choosing Cassandra as data store**:
     a. Highly Available: Due to Cassandra's multi master architecture, the data is highly available.
     b. Columner Storage: Due to columner storage, aggregate operations works faster.
     c. No-SQL Database: Flexiblity.
            
## Release 1 DFD:
[![CRent-DFD-Image.png](https://i.postimg.cc/vZB2R5J8/CRent-DFD-Image.png)](https://postimg.cc/XpRkdBNt)
