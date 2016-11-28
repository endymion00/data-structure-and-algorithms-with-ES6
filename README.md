# Data Structures and Algorithms with ES6


![](https://i.blogs.es/545cf8/es6-logo/original.png) ![](https://lh3.googleusercontent.com/a4Xrc-8oQLu05mOrNPuvA_o2nZEIEnOoTH4wB91Slw_hCvuIu_Qgi440bK9mC8ml-KA=w300)

This exercises are based from the book [Data Structures and Algorithms with JavaScript](http://shop.oreilly.com/product/0636920029557.do) - [by Michael McMillian (O’Reilly)](http://www.oreilly.com/pub/au/518) ISBN - 978-1-449-36493-9.

The purpose of this repo is to update the exercises to ES6 standards and to correct the errors from the examples that this book has.

## Examples in this repo

| **Num** | **Type** | **Exercises** | **Description** |
--- | --- | --- | ---
| 1.- | [Array](./02-chapter-Arrays.js) | 4 | The `Array` is the most common data structure in computer programming
| 2.- | [Lists](./03-chapter-List.js) | 5 | A `List` is an ordered sequence of data, where elements are not meant to be ordered.
| 3.- | [Stacks](./04-chapter-Stacks.js) | 3 | A `Stack` is an example of Last-in, First-Out (LIFO)
| 4.- | [Queues](./05-chapter-Queues.js) | 3 | A `Queue` is an example of First-in, First-Out (FIFO)
| 5.- | [Linked List](./06-chapter-1-Linked-List.js) | 4 | A `Linked list` is a collection of objects called nodes. Each node is linked to a successor node in the list using an object reference.
| 6.- | [Double Linked List](./06-chapter-2-Double-Linked-List.js) | 4 | Traversing a `Double linked list` are more efficient, since we no longer have to search for the previous node.
| 7.- | [Circular Linked List](./06-chapter-3-Circular-Linked-List.js) | 4 | The reason you might want to create a `Circular linked list` is if you want the ability to go backward through a list but don’t want the extra overhead of creating a doubly linked list.
| 8.- | [Dictionaries](./07-chapter-Dictionaries.js) | 3 | A `Dictionary` is a data structure that stores data as key-value pairs.
| 9.- | [Hashing](./08-chapter-Hashing.js) | 2 | `Hashing` is a common technique for storing data in such a way that the data can be inserted and retrieved very quickly. Hashing uses a data structure called a hash table. Although hash tables provide fast insertion, deletion, and retrieval, they perform poorly for operations that involve searching.
| 10.- | [Set](./09-chapter-Set.js) | 4 | A `Set` is a collection of unique elements. The elements of a set are called members. The two most important properties of sets are that the members of a set are unordered and that no member can occur in a set more than once.
| 11.- | [Binary Trees and Binary Search Trees](./10-chapter-Binary-Trees.js) | 4 | `Binary trees` are chosen over other more primary data structures because you can search a binary tree very quickly (as opposed to a linked list, for example) and you can quickly insert and delete data from a binary tree (as opposed to an array).
| 12.- | [Simple Graphs](./11-chapter-1-MatrixAdjencency-Graphs.js) | 2 | A graph consists of a set of vertices and a set of edges. A map is a type of graph where each town is a vertex, and a road that connects two towns is an edge. Edges are defined as a pair (v1, v2), where v1 and v2 are two vertices in a graph
| 13.- | [Complete Graphs](./11-chapter-2-ArrayListAdjecency-Graphs.js) | 2 | A complete graph is where all vertices are conected with each other.
| 14.- | [Sorting Algorithms](./12-chapter-Sorting-Algorithms.js) | 6 | Two of the most common operations performed on data stored in a computer are sorting and searching. The sorting algorithms are Bubble Sort, Selection Sort, Insertion Sort, Shell Sort and Quick Sort.
| 15.- | [Searching Algorithms](./13-chapter-Searching-Algorithms.js) | 6 | There are two ways to search for data in a list: sequential search and binary search. A sequential search is used when the items in a list are in random order; a binary search is used when the items in a list are in sorted order.


### To run the examples we need the following:

- NodeJS Installed
- Open Any Terminal and position it to the folder where the files are located
- execute the command: `$ node [file-name.js]`
