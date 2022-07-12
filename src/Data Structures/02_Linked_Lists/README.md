## 02. Linked Lists

In arrays, the data elements were placed in the memory in order. Hence, we were able to access any element using its corresponding index. However, if we scatter these elements at different places in the memory and store the location of the next element in the current element, we get a linked list. *(We will discuss more on this point in concept 1.)*

The principal benefit of a linked list over a conventional array is that the list elements can be easily inserted or removed without reallocation or reorganization of the entire structure because the data items need not be stored contiguously in memory or on disk, while restructuring an array at run-time is a much more expensive operation. Linked lists allow insertion and removal of nodes at any point in the list, and allow doing so with a constant number of operations by keeping the link previous to the link being added or removed in memory during list traversal.

On the other hand, since simple linked lists by themselves do not allow random access to the data or any form of efficient indexing, many basic operations — such as obtaining the last node of the list, finding a node that contains a given datum/value, or locating the place where a new node should be inserted — may require iterating through most or all of the list elements. The comparison of array vs. linked list is given below.

|  | Dynamic Array | Linked List |
| -- | -- | -- |
| Access n'th element | O(1) | O(n) |
| Insert or delete an element in the beginning | O(n) | O(1)|
| Insert or delete an element in the middle| O(n) | O(1)* |
| Insert or delete an element in the end| O(n) | O(1)*|
| Extra space required | 0 | O(n) |

> **'*' Condition:** The address of the deletion point or the insertion point should be known to us. Otherwise we will take O(n) time just to reach in the middle or the end in the linked list and all the benefit is lost.

Unlike arrays, linked lists are not much used for solving algorithmic problems. They have a limited usage but that limited usage is very important. Therefore, we can't ignore this data structure. 

<br/>

Here is the list of concepts related to the linked lists. 

| Topic | Description |
| --- | --- |
| [01. Insertion & Deletion of elements](./01_Insert_and_delete.md) | Understand how to create and modify a linked list by adding and removing elements from it. |
| [02. Traversing](./02_Traversal.md) | Access each element of the linked list & understand how to perform various operations where traversal is required |
| [03. Loops](./03_Loops.md) | Detect and remove a loop from the linked list |
| [04. Sorting](./04_Sorting.md) | Since we can't access the elements directly this time, understand how to sort an LL|
| [05. Reversal & Rotation](./05_Reverse_and_rotate.md) | Reverse and rotate an LL |
| [06. Additional Problems](./06_Additional_Problems.md) | Will discuss tricky & famous problems on LL | 
| [07. Circular Linked List](./07_Circular_linked_list.md) | After understanding singly linked list, it's time to quickly review circular linked list.
| [08. Doubly Linked List](./08_Doubly_Linked_List.md) | Like CLL, DLL is another variant of linked list and could be easily understood |

