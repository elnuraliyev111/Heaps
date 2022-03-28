# Max Heaps

MAX-HEAPS: PYTHON
Review
Nice work! You’ve implemented a MaxHeap class in Python. Heaps are useful because they’re efficient in maintaining their heap properties.

Let’s recap what we learned:

A max-heap tracks the maximum element as the element at index 1 within an internal Python list.
Max-heaps must maintain the heap property that the parent values must be greater than their children.
When adding elements, we use .heapify_up() to compare the new element with its parent; if it violates the heap property, then we must swap the two values.
In the next lesson, we’ll learn how to extract the root value of a heap as well as how to sort data using heapsort!

Instructions
Take a look at the final code in max_heap.py and script.py. Feel free to play around and edit the code to get a better understanding of heaps in Python!

# HEAPSORT: PYTHON
Review
Great job reaching the end of this lesson and implementing a heapsort algorithm in Python.

Let’s go over what we learned about heapsort:

A heapsort algorithm uses the heap data structure to organize data.
The first step to implement heapsort is to place the data inside a heap.
While the heap has more than one element, extract the largest value in the heap by swapping it with the right-most child and then removing it.
After we swap the root value and the last value, we must restructure the heap until every parent has a larger value than their children again.
Instructions
Take a look at the completed code. Feel free to edit the program to get a better understanding of heaps and heapsort.
