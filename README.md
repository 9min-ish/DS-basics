# DS-basics
Data structures are fundamental concepts in computer science and programming. They are ways to store and organize data to enable efficient access and modification. Here’s an overview of the basics of data structures:

### Types of Data Structures

1. **Primitive Data Structures**
   - **Integers**: Whole numbers (e.g., -2, 0, 42).
   - **Floats**: Numbers with fractional parts (e.g., -3.14, 2.71).
   - **Characters**: Single letters or symbols (e.g., 'a', 'Z', '1').
   - **Booleans**: Binary values (e.g., True, False).

2. **Non-Primitive Data Structures**
   - **Arrays**: A collection of elements, typically of the same type, stored at contiguous memory locations. They allow random access to elements using an index.
     ```python
     arr = [1, 2, 3, 4, 5]
     ```

   - **Linked Lists**: A sequence of elements, where each element points to the next. This allows for efficient insertion and deletion.
     ```plaintext
     head -> [data | next] -> [data | next] -> NULL
     ```

   - **Stacks**: A collection of elements that follows the Last In, First Out (LIFO) principle. Operations are typically `push` (add an item) and `pop` (remove an item).
     ```python
     stack = []
     stack.append(1)  # push
     stack.pop()      # pop
     ```

   - **Queues**: A collection of elements that follows the First In, First Out (FIFO) principle. Operations are typically `enqueue` (add an item) and `dequeue` (remove an item).
     ```python
     queue = []
     queue.append(1)  # enqueue
     queue.pop(0)     # dequeue
     ```

   - **Trees**: A hierarchical structure consisting of nodes, with a single root node and potentially many levels of additional nodes. Each node has zero or more child nodes.
     - **Binary Tree**: Each node has at most two children.
       ```plaintext
           1
          / \
         2   3
        / \
       4   5
       ```

   - **Graphs**: A collection of nodes (vertices) connected by edges. Graphs can be directed or undirected, weighted or unweighted.
     ```plaintext
     (A)---(B)
      |   / |
      |  /  |
      | /   |
     (C)---(D)
     ```

   - **Hash Tables**: A collection of key-value pairs, where each key is unique. The keys are hashed to generate an index at which the value is stored.
     ```python
     hash_table = {}
     hash_table['key'] = 'value'
     ```

### Operations on Data Structures

1. **Insertion**: Adding a new element to the data structure.
2. **Deletion**: Removing an element from the data structure.
3. **Traversal**: Accessing each element of the data structure.
4. **Searching**: Finding an element in the data structure.
5. **Sorting**: Arranging elements in a specific order.

### Choosing the Right Data Structure

The choice of data structure depends on various factors such as:

- **Data size and complexity**: For small datasets, simple structures like arrays or linked lists might be sufficient. For larger datasets, more complex structures like trees or hash tables might be necessary.
- **Operations needed**: If frequent insertions and deletions are required, linked lists might be better than arrays. For fast search operations, hash tables or binary search trees might be more efficient.
- **Memory usage**: Some data structures, like arrays, use contiguous memory locations and can be more memory efficient. Others, like linked lists, require extra memory for pointers.

### Example Usage in Programming

Here are some common examples of how data structures are used in programming:

- **Arrays**: Used for storing a list of items like numbers, names, etc.
- **Linked Lists**: Used in scenarios where frequent insertions and deletions occur, such as in implementing queues.
- **Stacks**: Used for undo mechanisms in software, expression evaluation, and syntax parsing.
- **Queues**: Used in scheduling algorithms, managing requests in servers.
- **Trees**: Used in databases and file systems for hierarchical storage.
- **Graphs**: Used in networking, social networks, and solving pathfinding problems.
- **Hash Tables**: Used in implementing associative arrays, database indexing, and caches.

Understanding these basics provides a strong foundation for more advanced topics in computer science and efficient programming practices.
