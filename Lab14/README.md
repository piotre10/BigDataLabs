### Data Modeling 
Data modeling is the process of creating a conceptual representation of data objects, the relationships between different data objects, and the rules. Data modeling techniques and methodologies are used to model data in a standard, consistent, predictable manner to manage data as a resource. It includes designing how the data will be stored, retrieved, and updated in a database system or a data warehouse.

### Cardinality 
In the context of databases, cardinality refers to the uniqueness of data values in a column, or the number of distinct values in a column. High cardinality means that the column contains a large percentage of totally unique values, and low cardinality means that the column data is not very unique. Understanding cardinality is important for selecting appropriate indexes for your database, and for optimizing queries.

### Normalization and Denormalization
Normalization is the process of structuring a relational database in accordance with a series of so-called normal forms to reduce data redundancy and improve data integrity. This often involves dividing larger tables into smaller tables and defining relationships between them.

Denormalization, on the other hand, is the process of combining tables to improve read performance. While normalization reduces redundancy, it can increase the complexity and performance cost of queries, as they may need to access multiple tables. Denormalization can make queries simpler and faster, but at the expense of potentially increased redundancy and decreased write performance.

### Datalake
A data lake is a storage repository that holds a vast amount of raw data in its native format until it is needed. While a hierarchical data warehouse stores data in files or folders, a data lake uses a flat architecture to store data. Each data element in a data lake is assigned a unique identifier and tagged with a set of extended metadata tags.

### Lakehouse
A Lakehouse is a new, open standard system that implements similar data structures and data management features to those in a data warehouse, directly on low-cost storage. It provides the best of both data lakes and data warehouses. It is designed to handle both analytical and operational workloads, from historical reporting to data science and machine learning. Unlike a data warehouse, it does not require the movement of data into a separate system and is thus more flexible.

###  OLAP Cube
An OLAP (Online Analytical Processing) cube is a data structure that overcomes the limitations of relational databases by providing rapid data analysis. It allows users to analyze information from multiple database dimensions. It's a multi-dimensional array of data that allows for complex analytical and ad-hoc queries with a rapid execution time.

###  DAX (Data Analysis Expressions)
DAX is a collection of functions, operators, and constants that can be used in a formula, or expression, to calculate and return one or more values. It's primarily used in Power BI, Analysis Services, and Power Pivot in Excel. DAX helps users create new information from data already in their model or reports.

