# Introduction to Data Modeling

## Learning Goals

- Define components of the **Entity Relationship Data Model**
- Define the **Entity Relationship Data Modeling Process**

## Introduction

Data modeling is the process of visualizing and representing data for storage.
A **data model** is a conceptual representation of the data,
the relationships between data, and rules that specify constraints on the validity of the data.
A data model can include diagrams, symbols, or text to represent data
and how it interrelates.

A data model is built around business needs.
Rules and requirements are defined
through feedback from business stakeholders (i.e. the client or end user).
The data model process begins by collecting information about business requirements
from the business stakeholders.  The requirements are then translated into a data
model.  The process is often iterative, with the data model continuously evolving to address
changing business needs.

## Entity Relationship Data Model

There are numerous data modeling methodologies,
each proposing a particular process and technique for representing data.
We will focus on the **Entity Relationship Data Model (ER Model)**,
which is popular for designing relational databases.
An ER model consists of:

- **Entities**: Entities represent people, places, things, events, or concepts for which
  data is processed and stored as tables.
- **Attributes**: Attributes are the characteristics or properties of an entity that are
  stored as table columns.
- **Relationships**: Relationships represents the associations between entities based on business
  rules or constraints, and are stored as foreign key columns.

## Entity Relationship Data Modeling Process

A data modeling process defines a workflow that includes
a sequence of tasks to be performed in an iterative manner.
The entity relationship data modeling process generally has this sequence of steps:

1. **Identify the entities**. The data modeling process begins with the identification
   of the things, events or concepts that the application must process and store.
   Each entity should be cohesive and logically discrete from other entities.
2. **Identify properties/attributes of each entity**.  Each entity can be differentiated
   from other entities because it has one or more unique properties, also called attributes.
   While two entities may have the same value for a particular property, the collective
   set of property values should be unique between entities.  The model should indicate
   attribute constraints (primary key, data type, unique, null, etc).
3. **Identify relationships between entities**. Each relationship defines an association between
   two or more entities, along with cardinality constraints. 

## Conclusion

A **data model** is a conceptual representation of the data,
the relationships between data, and rules that specify constraints on the validity of the data.
A data modeling process defines a workflow that includes a sequence of tasks
to be performed in an iterative manner.


## Resources

- [What is data modeling](https://www.ibm.com/topics/data-modeling)
