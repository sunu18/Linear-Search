# Linear-Search

Linear search is a simple search algorithm that works by iterating through each element in a list or array until the target value is found or the end of the list is reached. It is sometimes called a sequential search because it searches the elements in a sequence, one by one.

Here's how linear search works in pseudocode:

Set a flag variable to False to indicate that the target value has not been found yet.
Iterate through each element in the list or array:
a. If the current element matches the target value, set the flag variable to True and return the index of the current element.
If the end of the list is reached and the target value has not been found, return -1 to indicate that the target value is not in the list.
Here's an example of how linear search works:

Suppose we have the following list: [5, 7, 2, 4, 9, 11, 8]. We want to search for the target value of 9.

Set the flag variable to False.
Iterate through each element in the list:
a. The first element is 5, which does not match the target value.
b. The second element is 7, which does not match the target value.
c. The third element is 2, which does not match the target value.
d. The fourth element is 4, which does not match the target value.
e. The fifth element is 9, which matches the target value. Set the flag variable to True and return the index of the fifth element, which is 4.
In this example, linear search found the target value in five iterations, which is not very efficient for a large list or array. However, linear search is useful for small lists or arrays and is easy to implement.
