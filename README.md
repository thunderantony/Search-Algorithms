# Linear Search and Binary search

## Aim:

To write a program to perform linear search and binary search using python programming.

## Equipment’s required:

1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:

## Linear Search:

1. Start from the leftmost element of array[] and compare k with each element of array[] one by one.
2. If k matches with an element in array[] , return the index.
3. If k doesn’t match with any of elements in array[], return -1 or element not found.

## Binary Search:

1. Set two pointers low and high at the lowest and the highest positions respectively.
2. Find the middle element mid of the array ie. arr[(low + high)/2]
3. If x == mid, then return mid.Else, compare the element to be searched with m.
4. If x > mid, compare x with the middle element of the elements on the right side of mid. This is done by setting low to low = mid + 1.
5. Else, compare x with the middle element of the elements on the left side of mid. This is done by setting high to high = mid - 1.
6. Repeat steps 2 to 5 until low meets high

## Program:

i) #Use a linear search method to match the item in a list.

![Screenshot 2024-04-16 130431](https://github.com/thunderantony/Search-Algorithms/assets/149364638/e64a217b-ed6c-4bd5-87b1-5c28b15f36c7)


ii) # Find the element in a list using Binary Search(Iterative Method).

![Screenshot 2024-04-16 130504](https://github.com/thunderantony/Search-Algorithms/assets/149364638/0002cfdd-4ae1-4266-a8de-d51cff2a6b7a)


iii) # Find the element in a list using Binary Search (recursive Method).

![Screenshot 2024-04-16 130504](https://github.com/thunderantony/Search-Algorithms/assets/149364638/6cb11021-c375-48c6-8011-e1be842a119b)


## Output

i) #Use a linear search method to match the item in a list.

![Screenshot 2024-04-16 130448](https://github.com/thunderantony/Search-Algorithms/assets/149364638/0da2bac3-5e10-421f-a1b5-dac7efae3f80)

ii) # Find the element in a list using Binary Search(Iterative Method).

![Screenshot 2024-04-16 130518](https://github.com/thunderantony/Search-Algorithms/assets/149364638/02e22ca0-4d6e-4ddd-9be2-450499a6921e)


iii) # Find the element in a list using Binary Search (recursive Method).

![Screenshot 2024-04-16 130542](https://github.com/thunderantony/Search-Algorithms/assets/149364638/a8166830-2f86-467e-ad8f-2c2e83953c8a)


## Result

Thus the linear search and binary search algorithm is implemented using python programming.
