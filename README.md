# Linked-Lists

A linked list is a linear data structure, in which the elements are not stored at contiguous memory locations. The elements in a linked list are linked using pointers as shown in the below image:

![image](https://user-images.githubusercontent.com/125825670/234485396-a73be674-5e9a-4829-b8c1-05f36f0a3376.png)

Representation of Linked List

Let's see how each node of the linked list is represented. Each node consists:

a. A data item

b. An address of another node

We wrap both the data item and the next node reference in a struct as:

struct node

{

  int data;
  
  struct node *next;
  
};

Linked List Utility

Lists are one of the most popular and efficient data structures, with implementation in every programming language like C, C++, Python, Java, and C#.

Apart from that, linked lists are a great way to learn how pointers work. By practicing how to manipulate linked lists, you can prepare yourself to learn more advanced data structures like graphs and trees.

Linked List Applications:

1. Dynamic memory allocation

2. Implemented in stack and queue

3. In undo functionality of softwares

4. Hash tables, Graphs
