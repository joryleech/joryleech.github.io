---
layout: project
type: project
image: images/pathfindingLogo.png
title: Network Sharded Database
permalink: projects/networkShardedDatabase
date: 2018
labels:
  - Python
  - SQLite3
  - Sockets
  - SQL
summary: Integration of sharding algorithms over a networked connection for a database.
---


## Project Goal
This project was created to create a multi-node database, that acts as a modular and expanding system. The program requires only 2 nodes at a minimum to function: One being a catalog node that provides access information for a minimum of one (or zero if no data is currently stored) other nodes. 

## Skills Used
  The main resources used were:
  * Python
  * SQLite3
  * Sockets
  
## Personal Involvement
I was the sole developer and resource creator of this project.
  
## End Product
  The end product was a combination of 3 programs: Client, Variable Database Node, and Catalog Node. 
  
  **Catalog Node:** The catalog node acted as Database DNS of sorts. In order for the program to work, the user must have access to the database node from the client. The database node stores information about each of the other nodes, and is update upon creation or deletion and should most often be accessed via tablename. This information includes:
   * Tablename: This is the most often searched piece of data, and is not unique. Meaning a single table can span multiple nodes from multiple entries.
   * IP Address: To access the node, this also includes port to access it from. Because of this the program can be run off of a single computer via multiple port connections.
   * Partition Method and Parameters: This allows the data on a single table to be striped across different nodes, if smaller more numerous nodes are more important for a users application. This is mentioned in depth further. 
   
   This program otherwise acts as a normal database node, using a selection operator and returning all databases that fall true under a given query.
   
   **Variable Database Node**
   

## Screenshots



