# Linked-List
##Code 1
1. Start
2. Declare a global variable int x.
3. Define a structure node with integer data and a pointer to the next node.
4. Define a class named linked_list with a private member head (a pointer to the first node).
5. Inside the linked_list class:
   a. Define a public member function add_node_beg():
      i. Create a new node (newnode) dynamically using malloc.
      ii. Input: Read data from the user and store it in x.
      iii. Set newnode's data to x and next to NULL.
      iv. Set newnode's next to the current head.
      v. Set head to newnode.
   b. Define a public member function del_node_beg():
      i. Similar to add_node_beg(), create a new node and read data from the user.
      ii. Check if the list is empty (head is NULL). If empty, display an error message.
      iii. Otherwise, update head to point to the second node and free the memory of the first node.
   c. Define a public member function add_node_end():
      i. Similar to add_node_beg(), create a new node and read data from the user.
      ii. Check if the list is empty (head is NULL). If empty, set head to newnode.
      iii. Otherwise, traverse the list to find the last node and update its next to point to newnode.
   d. Define a public member function del_node_end():
      i. Similar to add_node_beg(), create a new node and read data from the user.
      ii. Check if the list is empty (head is NULL). If empty, display an error message.
      iii. Otherwise, if there is only one node, free its memory and set head to NULL.
      iv. Otherwise, traverse the list to find the second last node, set its next to NULL, and free the memory of the last node.
   e. Define a public member function display_l1():
      i. Initialize a temporary pointer temp to the head.
      ii. Iterate through the list using a loop until temp is NULL:
         - Output: Print temp's data followed by "->".
         - Update temp to point to the next node.
      iii. Output: Print "NULL" and a newline to signify the end of the list.
6. End
The program starts, and a global variable x is declared to store data entered by the user.
A structure node is defined to represent a node in the linked list, containing data and a pointer to the next node.
A class linked_list is defined with member functions to manipulate the linked list, including adding nodes at the beginning and end, deleting nodes from the beginning and end, and displaying the linked list.
The member functions of the class are implemented to handle various operations on the linked list. These functions use dynamic memory allocation and pointer manipulation to create, update, and delete nodes.
The algorithm provides a step-by-step description of the operations performed in each member function of the linked_list class.



##Code 2
