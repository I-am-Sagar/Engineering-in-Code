## 06. Binary Search Trees

In computer science, a *binary search tree (BST)*, also called an *ordered or sorted binary tree*, is a rooted binary tree data structure with the key of each internal node being greater than all the keys in the respective node's left subtree and less than the ones in its right subtree. The time complexity of operations on the binary search tree is directly proportional to the height of the tree.

<img src="../img/bst.png" width="250">

Binary search trees allow binary search for fast lookup, addition, and removal of data items. Since the nodes in a BST are laid out in such a way that each comparison skips about half of the remaining tree, the lookup performance is proportional to that of binary logarithm. BSTs are devised in the 1960s for the problem of efficient storage of labeled data and are attributed to *Conway Berners-Lee* and *David Wheeler.*

The performance of a binary search tree is dependent on the order of insertion of the nodes into the tree since arbitrary insertions may lead to degeneracy; several variations of the binary search tree can be built with guaranteed worst-case performance. The basic operations include: *search, traversal, insert and delete*. BSTs with guaranteed worst-case complexities perform better than an unsorted array, which would require linear search time.

The complexity analysis of BST shows that, on average, the insert, delete and search takes *O(log n)* for *n* nodes. In the worst case, they degrade to that of a singly linked list: *O(n)*.

<br/>

Here is the list of topics related to binary search tree. 

| Concept | Description |
| -- | -- |
| [01. Search, Insert & Delete in BST](./01_Search_insert_delete.md)| Understand the basic operations for which BST was developed |
| [02. Traversal in BST](./02_Traversal.md) | Traversal in BST is same as that in BT; the only catch would be how to use the BST property in traversal-based problems |
| [03. LCA](./03_LCA.md) | LCA of BST could be calculated in *O(log n)* time, unlike in BT where it takes *O(n)* time |
| [04. Interval Trees](./04_Interval_Tree.md) | A very nice modification of BST concept to work with intervals |
| [05. Additional Problems](./05_Additional_problems.md) | Some tricky problems on BSTs |

