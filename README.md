
# Binary Search in C

Binary search is an algorithm that is used to search for an element in a sorted array by repeatedly dividing the search interval in half. The algorithm works by comparing the middle element of the array to the target value, and then recursively searching either the left or right half of the array depending on whether the target value is greater than or less than the middle element.

the binary_search() function takes four arguments: the sorted array arr, the left and right indices of the search interval (left and right), and the target value target. The function returns the index of the target value in the array, or -1 if the target value is not found.

The while loop in the binary_search() function continues until the search interval is empty, i.e., left is greater than right. The mid variable is calculated as the middle index of the search interval.

