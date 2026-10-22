The Job Scheduling problem, which involves ordering tasks with dependencies, is a classic and 
fundamental problem in computer science. It can be efficiently modeled as a graph traversal 
problem. This project implements a job scheduler by representing tasks and their prerequisites as 
a Directed Acyclic Graph (DAG). 
 
The Topological Sort algorithm is used to determine a valid linear ordering in which the jobs can 
be executed. In this model, each job is represented as a node, and a dependency (e.g., "Job A must 
finish before Job B can start") is represented as a directed edge from A to B. 
 
This project utilizes Kahn's algorithm, a BFS-based approach to topological sorting, which ensures 
that no job is scheduled before all its prerequisites are completed. This project demonstrates the 
practical application of graph data structures (DAGs) and traversal algorithms in solving real
world dependency resolution and scheduling problems.
