# Queue Data Structure Implementation in Python

This is a Python implementation of a **Queue** data structure using lists. A **Queue** follows the **First-In, First-Out (FIFO)** principle.

## Key Features:
- **Head**: Points to the first element in the queue.
- **Tail**: Points to the last element in the queue.
- **Enqueue**: Adds data at the tail of the queue.
- **Dequeue**: Removes data from the head of the queue.

## Uses:
- Accessing events in the order they occur.
- Preserving the original sequence of data.
- Handling tasks in the order they arrive (e.g., print queues, task scheduling).

## Advantages:
- **O(1) time complexity** for enqueue and dequeue operations.
- Two access points: Head (removal) and Tail (insertion).

## Limitations:
- Cannot insert, edit, or traverse the queue directly.
- Limited by the available space (fixed-size queues).
