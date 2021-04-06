**Database Normalization**
Database normalization is a process used to organize a database into tables and columns. The main idea with this is that a table should be about a specific topic and only supporting topics included.

**Reasons for Database Normalization**
There are three main reasons to normalize a database. The first is to minimize duplicate data, the second is to minimize or avoid data modification issues, and the third is to simplify queries.

**Insert Anomaly**
There are facts we cannot record until we know information for the entire row. In our example we cannot record a new sales office until we also know the sales person. Why? Because in order to create the record, we need provide a primary key. In our case this is the EmployeeID.

**Update Anomaly**
In this case we have the same information in several rows. For instance if the office number changes, then there are multiple updates that need to be made. If we don’t update all rows, then inconsistencies appear.

Deletion Anomaly Deletion of a row causes removal of more than one set of facts. For instance, if John Hunt retires, then deleting that row cause us to lose information about the New York office.