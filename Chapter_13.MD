# Stacks
* stack is a data structure similar to stacked plates. It follows a last in first out
* stacks are used for push or pop, actions that either take off or put on from top
* stacks are mainly used as return address for functions
* stacks pass data in between functions
* push operation add element to the top of the stack
* pop operation removes the element at the top of the stack
* peek operation takes the top of the stack without actually removing it from the pile
* bracket matching is when the numbers within closed brackets match the ones outside of the bracket

# Queues
* queue data structure is a special type of list
* queue follows the practice of first in first out
* List-based queue is a simple queue
* enqueuer uses the insert method to put items in the queue
* dequeuer method is used for removing items from the queue
* stack-based queue is when two stacks are used for one top of operations in terms of either pop or push
* enqueuer only receives information/data
* dequeuer operation is a bit more complicated. This requires the enqueue operation for that operation can delete from the queue. So it uses the dequeuer operation to take out data
* node-based   is a doubly linked list should it enable FIFO way of accessing data
* queue class is very similar to a doubly linked list class
* queues play a big role in computer like printer functionality

# hashing and symbol tables
* dictionaries are built with hashing tables
* hashing is converting data from a certain into a fixed size
* perfect hashing is when each string is guaranteed to be unique
* there is such things as collisions because two strings have the same hash value
* hash table is a list where elements are accessed by words instead of indexes, like a dictionary
* you can add or take elements with put or get functions
* get function returns the value associated with the key
* it is possible to use keys with non-string values
* chaining is a strategy for resolving conflicts and avoiding the limits to the numbers of elements in a hash table
* symbol tables keep track of symbols that have been declared and information about them
