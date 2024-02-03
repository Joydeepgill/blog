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






[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
