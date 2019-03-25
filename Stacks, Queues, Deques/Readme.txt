array_stack:
LIFO stack implementation using a Python list as underlying storage.

array_queue:
FIFO queue implementation using a Python list as underlying storage.

exceptions:
Base class for Empty exception.

linked_queue:
FIFO queue implementation using a singly linked list for storage.

circular_queue:
Queue implementation using circularly linked list for storage. Ideal for round-robin schedulers, with rotate function.

doubly_linked_base:
Base class for doubly linked lists.

linked_deque:
Double-ended queue implementation basedf on a doubly linked list.

positional_list:
A sequential container of elements allowing positional access.

Finding an element at a given index within a linked list requires traversing the list incrementally from its beginning or end, counting elements as we go.



Array Advantages:
O(1)- time access to an element based on an integer index.
Generally smaller constants for O(n) operations.
Proportionally less memory usage.

Linked Advantages:
Worst-case time bounds for operations.
O(1)- time insertions and deletions at arbitrary positions.

Both are referential structures in Python.
