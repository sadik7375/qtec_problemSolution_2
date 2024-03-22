# qtec_problemSolution_2


#I solved the problem using binary search algorithm(C++ code). Binary search is chosen because it efficiently finds the index of the target element better than linear search algorithm in a sorted array. The time complexity of binary search is O(log n).I am explaining my code step by step.


1st step: I Defined two variable left and right which are the range of indices to search within the array.

2nd step:Doing following steps until left is greater than right:

3rd step:Get the middle index mid as the average of left and right.

4th step:Then compare the element at index mid with the target:
If they are equal, return mid as the index of the target.
If the element at index mid is less than the target, update left to mid + 1 to search in the right half of the array.
If the element at index mid is greater than the target, update right to mid - 1 to search in the left half of the array.


5th step: If the loop terminates without finding the target (left > right), return left as the index where the target would be inserted to maintain sorted order.

