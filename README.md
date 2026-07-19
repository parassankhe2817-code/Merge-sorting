# Merge-sorting

DEFINATION : Merge Sort is a divide-and-conquer sorting algorithm that sorts an array or list by repeatedly dividing it into two smaller halves until each subarray contains only one element. It then merges these subarrays back together in sorted order to produce the final sorted array.

# Algorithm
1)Create two temporary arrays:

2)Left array = A[low...mid]
3)Right array = A[mid+1...high]
4)Compare the first elements of both arrays.
5)Copy the smaller element into the original array.
6)Move to the next element in the array from which the element was copied.
7)Repeat Steps 2–4 until one temporary array becomes empty.
8)Copy the remaining elements (if any) from the left array into the original array.
9)Copy the remaining elements (if any) from the right array into the original array.
10)Stop.
