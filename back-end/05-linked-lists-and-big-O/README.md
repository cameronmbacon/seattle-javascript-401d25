![cf](http://i.imgur.com/7v5ASc8.png) 05: Linked Lists and Big Oh Notation
=====================================

## Learning Objectives
* Students will be able to determine and describe the runtime complexity of an algorithm
* Students will understandt he concepts of the linked list data structure

## Resources
* Watch [linked lists] (https://www.youtube.com/watch?v=njTh_OwMljA)
* Skim [linked list wiki](https://en.wikipedia.org/wiki/Linked_list)
* Read [simple wiki big o]
* Watch [hacker rank big o video]
* Skim at [big o cheat sheet]


## Outline

![linked-list](https://s3-us-west-2.amazonaws.com/slugbyte-assets/linked-list.svg)

#### Singly Linked List
* there are no FILO/FIFO-style constraints on singly linked lists
  * **FILO** - first in last out
  * **FIFO** - first in first out
* singly linked lists contain a series of nodes where each node contains a value as well as a `next` property - this points to the next node in a line of interconnected nodes
* operations that can be performed on singly linked lists include:
  * insertion (ie: `append` and `prepend` methods)
  * deletion (ie: `remove` method)
  * traversal (ie: `find` method)
* singly linked lists can contain pointers to both the head and the tail, yet this is not a common or simplified implementation and is usually reserved for doubly linked lists

### Big O
Big-o is a way of describing the speed and memory usage of an algorithm. Algorithms can run faster or slower given a specific input, thus we only use big-o to describe the worst case scenario. The letter "n" is used to describe the number of items/calculations an algorithm is operating on.

If an algorithm only makes single statements in the worst case, it is said that the algorithm runs with an "O(1)" runtime.  This runtime is also called constant time.

If an algorithm recursively cuts it's iteration in half from "n" until 1, it is said that the algorithm runs with an "O(log(n))" runtime. This runtime is also called logarithmic time.

If an algorithm runs through every item, it is said that the algorithm runs with an "O(n)" runtime. This runtime is also called linear time.

If an algorithm runs through a list of "n" items "n" times it is said that the algorithm runs with an "O(n^2)" runtime. This runtime is also called quadratic time.


[simple wiki big o]: https://simple.wikipedia.org/wiki/Big_O_notation
[hacker rank big o video]: https://www.youtube.com/watch?v=v4cd1O4zkGw
[Big O Cheat Sheet]: http://bigocheatsheet.com/
