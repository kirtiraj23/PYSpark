
## Introduction

#### BigData
##### - 
Data which easily can fit into your local system as per your scale like 0-64 GB of RAM,bt when you have larger datasets that you can't fit in your local Computer:--

When data is exceptionaaly huge then it can be managed in following ways:

1.Try usinga SQL database to move storage to Hard drive instead of RAM.

2. Or use a distributed system that distributes tha data to multiple machines

##### Advantages of distributing the data over didtributed Systems:-

1. A local Process will use the computation resources of a single machine, where a distributed process has access to computational resources across a number of machine connected through a network.

2. There will always be easy Scaling for distributed systems , you can just add more machines and increase the Space and Usage ,instead Single Computer will always have limited memory.

3. distributed system has a fault tolerance ,its like back up even if one system goes down, you will have one or many copies existing over the distributed network.


#### Hadoop
##### -
1. Hadoop is a way to distribute very large files across multiple machines.

2. It uses the Hadoop Distributed file system.

3. HDFS allows a user to work with large Data sets.

4. HDFS also dulplicates blocks of data for fault tolerance.

5. It also uses EMR,EMR does computation on that data.

#### Distributed Storage-HDFS
##### -
1. HDFS will use Blocks of Data with a size of 128 MB by default

2. Each of these blocks is replicated 3 times.

3. The blocks are distributed in this way to support fault tolerance.

4. Smaller blocks will provide more parallelization during processing.

5. Multiple copies of a block prevent loss of data due to failure of a node.

#### Distributed Storage-MapReduce
##### -

1. MapReduce(MR) is a way of splitting a computation task to a distributed set of files.

2. It consists of a Job Tracker and Multiple Task Trackers.

3. The Job Tracker sends code to run on the Task Trackers.

4. The Task Trackers allocate CPU and memory for the task and monitor the task on the worker nodes.

#### Spark RDDs
##### -
1. RDD-- Resilient Distributed Systems

2. It has four features:-
##### Distributed Collection of data

##### Fault Tolerant

##### Parallel Operation Partitioned

##### can use many data sources

3. RDDs are lazily evaluated, immutable and Cacheable.

4. we have two types of spark Operations
---Transformations
---Actions

5. Transformations are a definition to implement

6. Actions perform on the definition of Transformations.




