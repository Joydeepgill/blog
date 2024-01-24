---
layout: post
title:  "What are binary trees?"
date:   2023-11-27 18:56:51 -0500
categories: jekyll update
---
Binary trees can be thought of as a pointer-based data structure which resemble a tree. They have a root node, which can be thought of as the entry point into the tree. The root node has no parent. 

Each node contains a value, as well as a left and right pointer. Child nodes also have a parent pointer. The leaf nodes do not have left and right pointers.   

See the image below for an example of a binary tree: 

[TODO -- Insert image of BST]


You can go from the root node to any other node in the tree in O(logn) traversals. 

Depth: How many pointers must I follow to get to a certain node. Can be thought of as the number
of edges from X upto the root node. The root node has a depth of 0.  
Height: The height of a node is the number of edges on the longest path from the node to a leaf node. 
The leaf node has a height of 0. 

Note: N = total # of nodes in BST

Time Complexities: 
 Searching: O(logn)

 Insertion: 
 0(n) (worst case)
  - Note: The tree has to be either skewed to the right or the left.  

O(1) (best case)
  - Note: this occurs when the tree is skewed to the right, and the node being inserted belongs to the 
  left subtree (or vice versa). 
 
 **TODO ~ Deletion: 
  - 


{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
