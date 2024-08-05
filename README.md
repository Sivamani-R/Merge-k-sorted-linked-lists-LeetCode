# Merge k Sorted Lists

This repository contains an implementation of a solution to merge k sorted linked lists into one sorted linked list. The solution is written in Python.

## Solution

The `Solution` class contains a method `mergeKLists` that takes a list of `ListNode` objects and merges them into a single sorted linked list.

## Explanation

1. **Input Check**: The function first checks if the input list `lists` is empty or contains only `None`. If so, it returns `None`.
2. **Extract Values**: It iterates through each linked list in `lists`, extracting the values of the nodes and storing them in a list `l`.
3. **Sort Values**: The list `l` is then sorted.
4. **Rebuild Linked List**: A new linked list is constructed using the sorted values from `l`.
5. **Return Result**: The function returns the head of the newly created sorted linked list.

## Usage

To use this solution, create instances of `ListNode` to form your input linked lists, and then call the `mergeKLists` method of the `Solution` class.

## Notes

- This implementation extracts values from the nodes into a list, sorts them, and then constructs a new linked list. This approach has a time complexity of O(N log N), where N is the total number of nodes.
- This is a straightforward solution, but more efficient solutions exist, such as using a priority queue (min-heap) to merge the linked lists.

Feel free to use, modify, and distribute this code. Contributions and improvements are welcome!
