---
layout: post
title:  "What are Graphs?"
date:   2023-11-27 18:56:51 -0500
categories: jekyll update
---

Graphs are made up of a collection of entities called nodes/vertices, connected to each other through a
set of edges. Edges can be connected to nodes in any possible way (unlike BSTs). A graph G can be though of as a set of ordered pairs with a set of V vertices and a set E of edges: G = (V, E) 

Note: In an ordered pair, the order matters. Whereas, in an unordered pair is a set containing 2 unordered elements. For intance, the unordered pair {a, b} = {b, a}. In a ordered set (a, b) != (b, a). 

There are 2 types of edges in a graph: 
- Directed edge (directed edge in which connection is one way) 
  - graph w/ all directed edges is called digraph  
  -> Example: Interlinked webpages (webpages with links that lead to other webpages) on the internet can be represented as a directed graph. Directed since the relationship is not mutual (if page A has a link to 
  page B, its not necessarily the other way around). 
- Unidirected edge (undirected edge where connection is 2 way) 
  -> Example: Social network (Facebook) graph (edges represent the connection w/
  people). Node would be user in graph & if they're friends there'd be an edge connecting them. 
  This is an undirected graph becuase a friendship is a mutual relationship.

See the image below for an example of a graph: 

![Alt Text](https://www.boardinfinity.com/blog/content/images/2023/01/Graphs-in-DSA.png)


Note: There are weighed and unweighed graphs. Weighed edges are edges that have numerical values 
assosiated with them. Unweighed edges are those without numerical values. 

|v| = # of vertices 
|E| = # of edges 
 N = # of nodes 

Self-loop/loop: A vertex that has an edge pointing to itself.  

Multiedge/parallel Edges: edges which have the same end vertices.  

Simple Graph: graphs with no self-loops or multi-edge.  

Note: In a directed graph, the number of edges would be between 0 <= |E| <= N(N-1). 

Note: In a undirecited graph, the # of edges would be between 0 <= |E| <= N(N-1)/2. This is 
true only for a SIMPLE GRAPH.  


Dense: graph is called dense if number of edges in graph is close to the maximum possible edges. 
Sparse: graph is called sparse if the # of edges in a graph is very little. (The number of edges wouldn't be close to the maximum). Sometimes, they'd be close to the number of vertices. 

###### What is a walk? 
Its a sequence of vertices, where adjacent pair of vertices are connected by an edge. In a walk, you can 
repeat vertices.  


###### What is a Simple Path/Path? 
A path where no vertices (and thus, edges) are repeated. Can also be thought of as a path 
where there are distinct vertices.  


###### What is a trail?
A walk where vertices can be repeated but no edges can be repeated. 


###### Strongly connected graph? 
If every single vertex is reachable from every other vertex, then the graph is strongly connected. 
(Note: if its a undirected graph, we call it connected, otherwise its called strongly connected). 
Below is an example of a strongly connected graph: 


![Alt Text](https://inst.eecs.berkeley.edu/~cs61bl/r//cur/graphs/SC.png)

###### Closed walk/cycle? 
Graph where neither edges or vertices can repeat, however the starting and ending vertices
are the same. Length of the walk > 0. 


###### Simple cycle? 
No reptition other than start and end vertices. 


###### Acyclic graph? 
A graph with no cycle. 

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
