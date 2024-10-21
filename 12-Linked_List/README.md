# Linked List Overview

A **linked list** is a linear data structure that consists of a sequence of elements called nodes. Each node contains two components:
- **Data**: The value stored in the node.
- **Pointer (or Reference)**: A reference to the next node in the sequence.

Unlike arrays, linked lists do not require contiguous memory allocation, which allows for efficient insertion and deletion of elements.

## Types of Linked Lists

1. **Singly Linked List**:
   - Each node points to the next node in the sequence.
   - The last node points to `null`, indicating the end of the list.
   - Suitable for traversing in one direction.

   ![Singly Linked List](https://upload.wikimedia.org/wikipedia/commons/6/67/Singly-linked-list.svg)

2. **Doubly Linked List**:
   - Each node contains two pointers: one pointing to the next node and one pointing to the previous node.
   - Allows for traversal in both directions.

   ![Doubly Linked List](https://upload.wikimedia.org/wikipedia/commons/3/37/Doubly-linked-list.svg)

3. **Circular Linked List**:
   - The last node points back to the first node, forming a circle.
   - Can be singly or doubly circular linked lists.

   ![Circular Linked List](https://upload.wikimedia.org/wikipedia/commons/d/d5/Circularly-linked-list.svg)

## Advantages of Linked Lists

- **Dynamic Size**: Linked lists can grow and shrink in size dynamically, unlike arrays that have a fixed size.
- **Efficient Insertions/Deletions**: Adding or removing elements does not require shifting, making it faster (O(1) for insertions/deletions at the beginning or end).
- **No Memory Wastage**: Memory is allocated as needed, preventing wastage from unused space.

## Disadvantages of Linked Lists

- **Memory Overhead**: Each node requires extra memory for a pointer/reference.
- **Sequential Access**: Elements cannot be accessed directly; traversal is required, leading to O(n) time complexity for searching.
- **Cache Locality**: Poorer cache performance compared to arrays due to non-contiguous memory allocation.

## Basic Operations

1. **Insertion**:
   - At the beginning
   - At the end
   - At a specific position

2. **Deletion**:
   - From the beginning
   - From the end
   - From a specific position

3. **Traversal**:
   - Visiting each node in the list.

4. **Searching**:
   - Finding a node with a specific value.

