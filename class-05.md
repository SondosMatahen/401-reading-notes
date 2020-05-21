# Class-05
## Linked Lists

#### Linked List
A Linked List is a sequence of Nodes that are connected/linked to each other. The most defining feature of a Linked List is that *each Node references the next Node in the link*.

`A data structure that contains nodes that links/points to the next node in the list.`


#### Linked List types

- **Singly Lists :** Singly refers to the number of references the node has. A Singly linked list means that there is only one reference, and the reference points to the Next node in a linked list.
- **Doubly Lists :** Doubly refers to there being two (double) references within the node. A Doubly linked list means that there is a reference to both the Next and Previous node.


#### Elements of Lists
  - **Node :** the individual items/links that live in a linked list. Each node contains the data for each link.
  - **Next :** Each node contains a property called Next. This property contains the reference to the next node.
  - **Head :** The Head is a reference type of type Node to the first node in a linked list.
  - **Current :** The Current reference is a reference type of type Node that is currently being looked at.


#### How do we treverse linked lists?
  - When traversing a linked list, we depend on the `Next` value in each node to guide us `where the next reference is pointing`. 

  - The best way to approach a traversal is through the use of a **`while()`** loop. This allows us to continually check that the Next node in the list is not null.
  
  - When traversing through a linked list, the Current node is the most helpful. The Current will tell us where exactly in the linked list we are and will allow us to move/traverse forward until we hit the end.