# Week 2

## Chapter 7: Structuring System Process Requirements

### Process Modeling

**process modeling**: graphical representation of functions and processes that capture, manipulate, store, and distribute data between a system and components of a system

**data flow diagram (DFD)**: a picture of the moment of data between external entities and the processes and data stores within a system

* Represents both physical and logical systems
* Not flow charting
* Useful for depicting purely logical information flows

#### DFD Terms

* **data flow**: data in motion
* **data store**: data at rest
* **process**:  the work or actions performed on data so they are transformed, stored, or distributed
* **source / sink**: the origin and/or destination of data, also know as external entity

DFD represents a system's major processes, data flows, and data stores at a *high level of detail*.

* **Context diagrams** are the highest level view of a process. They are an overview of an organizational system that shows the system boundaries, external entities that interact with the system, and the major information flows between the entities and the system.

### Rules Governing Data Flow Diagramming

#### Process

1. No process can only have outputs, meaning it would make data from nothing. If it only has outputs, it is a _source._
2. No process can have only inputs, i.e. a black hole. if it only it has inputs, it is a *sink.*
3. A process has a verb phrase label.

#### Data Store

1. Data cannot move directly from one data store to another data store. Data must be moved by a process.
2. Data cannot move directly from an outside source to a data store (similar reasoning to 4).
3. Data cannot move directly to an outside sink from a data store (similar reasoning to 4).
4. A data store has a noun phrase label.

#### Source / Sink

1. Data cannot move directly from a source to a sink. It must be moved by a process if the data is of any concern to our system.
2. A source/sink has a noun phrase label.

#### Data Flow

1. A data only has only one direction of flow between symbols
   * It may flow in both directions to show a read before an update, but is usually indicated by two separate arrows because they happen at different time.
2. A fork in a data flow means that exactly the same data goes from a common location to two or more different processes, data stores, or sources/sinks.
3. A join in a data flow means that exactly the same data come from any of two or more different processes, data stores, or sources/sinks to a common location.
4. A data flow cannot go directly back to the same process it leaves.
5. A data flow to a data store means update (delete or change).
6. A data flow from a data store means retrieve or use.
7. A data flow has a noun phrase label.

### Guidelines for Drawing DFDs

* **DFD completeness**: all necessary components have been included and fully described
* **DFD consistency**: the extent to which information contained on one level of a set of nested DFDs is also include on other levels
  * A violation would be a level-1 diagram with no level-0 diagram.
  * Data flow that appears on higher-level DFD but not on lower level.
* Timing
  * not represented well on DFDs
* Iterative Development - the first DFD you draw will rarely capture the system you are modeling, takes several tries
* Primitive DFD - when to stop decomposing processes
  * Easy to say stop when you've reached the lowest logical level but that is difficult to know.
  * More concrete rules are:
    * When you have reduced each process to a single decision, calculation or database operation (CRUD).
