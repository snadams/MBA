# Week 6

## Chapter 9: Designing Databases

### The Process of Database Design

Inputs allow you to make key physical database decisions including the following:

* Choosing a storage format (i.e. *data type*) for each attribute from the logical database model
* Grouping attributes from the logical database model into physical records (i.e. selecting a stored record or data structure)
* Arranging related records in secondary memory (hard disks and magnetic tapes) so that individual records and groups of records to be stored, retrieved and updated rapidly (file organization)
* Selecting media and structures for storing data to make access more efficient.

#### Deliverable and Outcomes

During logical database design you must account for every data element on a system input or output.

* Normalized relations are the

#### The Relational Database Model

**relational database model**: data represented as a set of related tables or relations

**relation**: a named, two-dimensional table of data. Each relation consists of a set of named columns and an arbitrary number of unnamed rows.

### Physical File and Database Design

What one looks for in physical design:

* Normalized relations, including volume estimates
* Definitions of each attribute
* Descriptions of where and when data re used: entered, retrieved, deleted, and updated
* Expectations or requirements for response time and data integrity
* Descriptions of the technologies used for implementing the files and database - range of required decisions

**field**: the smallest unit of named application data recognized by system software

**data type**: a coding scheme recognized by system software for representing organizational data

* The four main objectives when selecting a data type are:
  * Minimize storage space
  * Represent all values of the field
  * Improve data integrity of the field
  * Support all data manipulations desired on the field

## Video - [Database Programming Tutorial: Defining Table Relationships](https://youtu.be/V5DyvUfsboA)

## Video - [How to Work With Relationships in SQL Server](https://youtu.be/4q-keGvUnag)

## Video - [Relational Database Concepts](https://youtu.be/NvrpuBAMddw)