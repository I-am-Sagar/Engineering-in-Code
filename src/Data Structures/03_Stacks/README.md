## 03. Stacks

In computer science, a stack is an abstract data type that serves as a collection of elements, with two main principal operations:

* **Push**, which adds an element to the collection.
* **Pop**, which removes the most recently added element that was not yet removed.

The order in which elements come off a stack gives rise to its alternative name, **LIFO (last in, first out)**. Additionally, a peek operation may give access to the top without modifying the stack. The name *stack* for this type of structure comes from the analogy to a set of physical items stacked on top of each other. This structure makes it easy to take an item off the top of the stack, while getting to an item deeper in the stack may require taking off multiple other items first.

Considered as a linear data structure, or more abstractly a sequential collection, the push and pop operations occur only at one end of the structure, referred to as the top of the stack. This data structure makes it possible to implement a stack as a singly linked list and a pointer to the top element. A stack may be implemented to have a bounded capacity. If the stack is full and does not contain enough space to accept an entity to be pushed, the stack is then considered to be in an overflow state. 

<br/>

Following list of concepts related to stacks would be covered.

| Concept | Description | 
| --- | --- |
| [01. Implementation](./01_Implementation.md) | Understand the implementation details of stack|
| [02. Design Problems](./02_Design_problems.md) | There are certain problems in which they ask us to design a special kind of stack with some additional feature |
| [03. Operations on Stacks](./03_Operations.md) | Will see how to perform various operations like reversing, sorting, etc. on the stack | 
| [04. Applications of Stacks](./04_Applications.md) | Understand various applications of stacks i.e. instances where they are useful |
| [05. Additional Problems](./05_Additional_problems.md) | Tricky & famous problems where using a stack would be useful |
