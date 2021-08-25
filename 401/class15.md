## Trees

* Node - A Tree node is a component which may contain it’s own values, and references to other nodes
* Root - The root is the node at the beginning of the tree
* K - A number that specifies the maximum number of children any node may have in a k-ary tree. In a binary tree, k = 2.
* Left - A reference to one child node, in a binary tree
* Right - A reference to the other child node, in a binary tree
* Edge - The edge in a tree is the link between a parent and child node
* Leaf - A leaf is a node that does not have any children
* Height - The height of a tree is the number of edges from the root to the furthest leaf

![](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-15/resources/images/BinaryTree1.PNG)

## Traversals

1- Depth First
2- Breadth First

> Pre-order: root >> left >> right
> In-order: left >> root >> right
> Post-order: left >> right >> root

![](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-15/resources/images/tree-example.png)

> Pre-order: A, B, D, E, C, F
> In-order: D, B, E, A, F, C
> Post-order: D, E, B, F, C, A

## Binary Search Trees
> A Binary Search Tree (BST) is a type of tree that does have some structure attached to it. In a BST, nodes are organized in a manner where all values that are smaller than the root are placed to the left, and all values that are larger than the root are placed to the right.

## Searching a BST

> Searching a BST can be done quickly, because all you do is compare the node you are searching for against the root of the tree or sub-tree. If the value is smaller, you only traverse the left side. If the value is larger, you only traverse the right side.
> Let’s say we are searching 15. We start by comparing the value 15 to the value of the root, 23.