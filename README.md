# Data-Structure-In-Java
Thid Repo Contains Data Structure in Java from the Introduction to Java Programming and Data Structure - Comperhensive Version - 12th Edithion - By LIANG
# Java-Data-Structure
<h3> WHAT IS DATA : </h3>

Data is the collection of different numbers, symbols, and alphabets to represent information.

<h3>WHAT IS DATA STRUCTURE : </h3>

A data structure is a group of data elements that provides the easiest way to store and perform different actions on the data of the computer. A data structure is a particular way of organizing data in a computer so that it can be used effectively. The idea is to reduce the space and time complexities of different tasks. 

The choice of a good data structure makes it possible to perform a variety of critical operations effectively. An efficient data structure also uses minimum memory space and execution time to process the structure.

A data structure has also defined an instance of ADT.ADT means ABSTRACT DATA TYPE. It is formally defined as a triplet.[ D,F,A]
<ul>
<li> D: Set of the domain.</li>  
<li> F:  the set of operations.</li> 
<li> A:  the set of axioms.</li> 
</ul>
Type of data structure :
<ol>
   <li>  Linear Data Structure.</li> 
   <li>  Non-Linear Data Structure.</li> 
   </ol>
  <h3>Linear Data Structure: </h3>

 Elements are arranged in one dimension ,also known as linear dimension.
 Example: lists, stack, queue, etc.
   <h3>Non-Linear Data Structure : </h3>

  Elements are arranged in one-many, many-one and many-many dimensions.
 Example: tree, graph, table, etc.
<h3>Data structures are used in various fields such as: </h3>
<ul>
<li>Operating system</li>
<li>Graphics</li>
<li>Computer Design</li>
<li>Blockchain</li>
<li>Genetics</li>
<li>Image Processing</li>
<li>Simulation etc.</li>
</ul>

<hr>

<h3>Some common Data Structure </h3>
<h4>1- Array </h4>
<p>An array is a collection of data items stored at contiguous memory locations. The idea is to store multiple items of the same type together. This makes it easier to calculate the position of each element by simply adding an offset to a base value, i.e., the memory location of the first element of the array (generally denoted by the name of the array). </p>

<img src="https://media.geeksforgeeks.org/wp-content/uploads/array-2.png" width="600px">
<p>For more Specific details : <a href="https://www.geeksforgeeks.org/array-data-structure/">Array</a></p>

<hr> 

<h4>2- Linked List </h4>
<p>Like arrays, Linked List is a linear data structure. Unlike arrays, linked list elements are not stored at a contiguous location; the elements are linked using pointers. </p>

<img src="https://media.geeksforgeeks.org/wp-content/cdn-uploads/gq/2013/03/Linkedlist.png">
<p>For more Specific details : <a href="https://www.geeksforgeeks.org/data-structures/linked-list/">Linked List</a></p>

<hr>

<h4>3- Stack </h4>
<p>Stack is a linear data structure which follows a particular order in which the operations are performed. The order may be LIFO(Last In First Out) or FILO(First In Last Out). In stack, all insertion and deletion are permitted at only one end of the list. </p>

<img src="https://media.geeksforgeeks.org/wp-content/uploads/20211218175824/geekstack1-300x171.png" width="600px">
<p>For more Specific details : <a href="https://www.geeksforgeeks.org/stack-data-structure/">Stack</a></p>

<hr>

<h4>4- Queue </h4>
<p> Like Stack, Queue is a linear structure which follows a particular order in which the operations are performed. The order is First In First Out (FIFO). In the queue, items are inserted at one end and deleted from the other end. A good example of the queue is any queue of consumers for a resource where the consumer that came first is served first. The difference between stacks and queues is in removing. In a stack we remove the item the most recently added; in a queue, we remove the item the least recently added.  </p>

<img src="https://media.geeksforgeeks.org/wp-content/uploads/20211218175931/geekqueue1-300x171.png" width="600px">
<p>For more Specific details : <a href="https://www.geeksforgeeks.org/queue-data-structure/">Queue</a></p>

<hr>

<h4>5- Binary Tree </h4>
<p> L Unlike Arrays, Linked Lists, Stack and queues, which are linear data structures, trees are hierarchical data structures. A binary tree is a tree data structure in which each node has at most two children, which are referred to as the left child and the right child. It is implemented mainly using Links. 

A Binary Tree is represented by a pointer to the topmost node in the tree. If the tree is empty, then the value of root is NULL. A Binary Tree node contains the following parts.   </p>
<ol>
<li>Data</li>
<li>Pointer to left Child</li>
<li>Pointer to right Child</li>
</ol>
<p>For more Specific details : <a href="https://www.geeksforgeeks.org/binary-tree-data-structure/">Binary Tree</a></p>

<hr>

<h4>6- Binary Search Tree </h4>
<p> A Binary Search Tree is a Binary Tree following the additional properties:   </p>
<ul>
<li>The left part of the root node contains keys less than the root node key.</li>
<li>The right part of the root node contains keys greater than the root node key.</li>
<li>There is no duplicate key present in the binary tree.</li>
</ul>
<p>For more Specific details : <a href="https://www.geeksforgeeks.org/binary-search-tree-set-1-search-and-insertion/">Binary Search Tree</a></p>

<hr>

<h4>7- Heap </h4>
<p> A Heap is a special Tree-based data structure in which the tree is a complete binary tree. Generally, Heaps can be of two types:  </p>
<ul>
<li>
<h3>Max-Heap</h3>
<p>In a Max-Heap the key present at the root node must be greatest among the keys present at all of its children. The same property must be recursively true for all sub-trees in that Binary Tree.</p>
</li>

<li>
<h3>Mini-Heap</h3>
<p>In a Min-Heap the key present at the root node must be minimum among the keys present at all of its children. The same property must be recursively true for all sub-trees in that Binary Tree.</p>
</li>

</ul>
<img src="https://media.geeksforgeeks.org/wp-content/uploads/20211218180132/MinHeapAndMaxHeap-300x180.png" width="600px">
<p>For more Specific details : <a href="https://www.geeksforgeeks.org/heap-data-structure/">Heap</a></p>




