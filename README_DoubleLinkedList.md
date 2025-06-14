Double Linked List Program
--------------------------------------

Author: Shashank Shekhar Rai
File: DoubleLinkedList.java

Description:
-------------
This Java program implements a Doubly Linked List and demonstrates key operations such as insertion at the beginning, end, and specific positions. It is designed to help understand bidirectional node linking using 'prev' and 'next' references.

Features Included:
------------------
1. Create a doubly linked list.
2. Insert a node at the beginning of the list.
3. Insert a node at the end of the list.
4. Insert a node at a specific position.
5. Display the linked list in forward order.

How to Run:
-----------
1. Compile the program:
   javac DoubleLinkedList.java

2. Run the program:
   java DoubleLinkedList

3. The program will execute a series of predefined insertions and display the list after each major operation.
   
Notes:
------
- The doubly linked list uses both `next` and `prev` pointers to enable bi-directional traversal.
- The position parameter in insertAtPosition is zero-based.
- Inserting at invalid positions is safely handled with a warning message.
- The display format visually separates elements using "<->".

Educational Use:
------------------
- Ideal for learning how doubly linked lists function.
- Helps understand node linking both forward and backward.
- Useful for preparing for data structures and algorithm interviews.
