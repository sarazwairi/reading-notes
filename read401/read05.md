# Linked Lists

## What is a Linked List

A Linked List is a sequence of Nodes that are connected/linked to each other. The most defining feature of a Linked List is that each Node references the next Node in the link.

![pic](Singly-Linked-List1.png)

Link − Each link of a linked list can store a data called an element.

Next − Each link of a linked list contains a link to the next link called Next.

LinkedList − A Linked List contains the connection link to the first link called First.

## Traversal Big O

The Big O of time for Includes would be O(n). This is because, at its worse case, the node we are looking for will be the very last node in the linked list. n represents the number of nodes in the linked list.

## Add nodes

* Head insertion: the newly added node is placed after the head node. The node order of head insertion is opposite to that of insertion. The following figure shows the process of head insertion

* Middle insertion method:The newly added node is inserted in the middle of the list. The following figure shows the process of intermediate interpolation

* Tail insertion method: the newly added node is placed at the end of the linked list. The following figure shows the process of tail insertion