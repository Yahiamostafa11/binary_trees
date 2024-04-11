# Binary Trees README

## What is a Binary Tree?
A binary tree is a hierarchical data structure composed of nodes, where each node has at most two children, referred to as the left child and the right child. The topmost node in a binary tree is called the root.

## Difference between a Binary Tree and a Binary Search Tree
While both are binary trees, a Binary Search Tree (BST) has an additional property: for each node in the tree, all nodes in its left subtree have values less than its value, and all nodes in its right subtree have values greater than its value. This property allows for efficient searching, insertion, and deletion operations.

## Gain in Time Complexity Compared to Linked Lists
Binary trees offer significant gains in time complexity compared to linked lists, especially for operations like searching, insertion, and deletion. While a linked list requires linear time complexity (O(n)) for these operations, a binary tree can achieve logarithmic time complexity (O(log n)) for balanced trees, making them more efficient for large datasets.

## Depth, Height, and Size of a Binary Tree
- **Depth:** The depth of a node in a binary tree is the length of the path from the root to that node.
- **Height:** The height of a binary tree is the length of the longest path from the root to a leaf node. It represents the maximum depth of the tree.
- **Size:** The size of a binary tree is the total number of nodes in the tree.

## Traversal Methods in Binary Trees
There are several traversal methods to navigate through a binary tree:
- **In-order traversal:** Visit the left subtree, then the root, and finally the right subtree.
- **Pre-order traversal:** Visit the root, then the left subtree, and finally the right subtree.
- **Post-order traversal:** Visit the left subtree, then the right subtree, and finally the root.
- **Level-order traversal:** Visit nodes level by level, starting from the root and moving to the next level.

## Types of Binary Trees
- **Complete Binary Tree:** A binary tree in which every level, except possibly the last, is completely filled, and all nodes are as far left as possible.
- **Full Binary Tree:** A binary tree in which every node has either zero or two children.
- **Perfect Binary Tree:** A binary tree in which all interior nodes have two children and all leaf nodes are at the same level.
- **Balanced Binary Tree:** A binary tree in which the height of the left and right subtrees of any node differ by no more than one.

