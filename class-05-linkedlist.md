## Linked List:
 A **Linked List** is the connected Nodes as a sequense, and every Node is a reference the next Node in the sequence.

 ## Type Of Linked List:

 ### 1. Singly Linked List:.
  A **Singly** linked list means that there is only one reference, and the reference points to the Next node in a linked list.
 ### 2. Dobly Linked List: 
 A **Doubly** linked list means that there is a reference to both the Next and Previous node.

 ### What is the Node:
  **Nodes** are the individual items/links that live in a linked list. Each node contains the data for each link.

#### Head:
**Head:** is a reference type of type Node to the first node in a linked list.

### Current:
The **Current** reference is a reference type of type Node that is currently being looked at.

### Traversal:
When traversing a linked list, you are not able to use a foreach or for loop. We depend on the Next value in each node to guide us where the next reference is pointing. The Next property is exceptionally important because it will lead us where the next node is and allow us to extract the data appropriately.

### Big O:
The **Big** O of time for Includes would be O(n). This is because, at its worse case, the node we are looking for will be the very last node in the linked list. n represents the number of nodes in the linked list.

###  dding a Node
- **Adding O(1):**
Order of operations is extremely important when it comes to working with a Linked List. What I mean by this is you must be careful that all references to each link/node is properly assigned.

- **steps to adding Node:**

Set Current equal to Head. This will guarantee us that we are starting from the very beginning.
We can then instantiate the new node that we are adding. The values passed in as arguments into the Add() method will define what the value of the Node will be.


