### Binary Tree Data Structure
A **tree** whose elements have at most 2 children is called a **binary tree**. Since each element in a **binary tree** can have only 2 children, we typically name them the left and right child.

### Binary Search Terminology
- **Root:** The root is the (first/top) Node in the **tree**
- **Left Child:**  the left  node of a root or node
- **Right Child:**  the left  node of a root or node
- **Edge:**  the link between a parent and child node
- **Leaf:**  node does not contain any children
- **Height:**   the number of **edges** from the **root** to the bottommost node

## Tree Traversals :
#### trees can be traversed in different ways:
- Depth First Traversals: is where we prioritize going through the depth (height) of the tree first.
  - **Inorder** (Left, Root, Right) : 4 2 5 1 3
  - **Preorder** (Root, Left, Right) : 1 2 4 5 3
  - **Postorder** (Left, Right, Root) : 4 5 2 3 1

### Adding a node:
Because there are no structural rules for where nodes are “supposed to go” in a binary tree, it really doesn’t matter where a new node gets placed.

### Binary Search Tree:
**Binary Search Tree** or **(BST)** is a node-based binary tree data structure which has the following properties:

- The left subtree of a node contains only nodes with keys lesser than the node’s key.
- The right subtree of a node contains only nodes with keys greater than the node’s key.
- The left and right subtree each must also be a binary search tree.

### Searching a BST
**Searching a BST** can be done just by comparing the node we are searching for against the root of the tree or sub-tree
