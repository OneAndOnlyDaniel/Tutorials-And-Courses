[YouTube](https://www.youtube.com/watch?v=8hly31xKli0)

2023-01-14

# Introduction to Algorithms
# Introduction to Data Structures
If you want to add a class to your python terminal usage you can use
`python -i linked_list.py`

If you want to output better information to the console about your class you can use the intrinstic function
`__repr__(self)`
which returns a string, this string then gets printed to the console.

Formatting strings can either be done using `.format()` or by using
`"<Node data: %s>" % self.data`

Linked lists are interesting for students who are starting with data structures but for practical applications there are much better data structures.

We implement Merge Sort now, which will work with a Divide and Conquer approach, we split the list into two pieces, and call merge sort recursively on those parts. empty and 1-element lists are already sorted, after breaking up the array into 0 or 1 element pieces we combine them and while combining we already sort them.

If we want to return multiple elements we don't have to do
`return [a, b]`
to return them as a list we can just return it like
`return a, b`
and then get them by
`a, b = split(myList)`

Implemented Merge Sort for Linked list. 

# Algorithms: Sorting and Searching
In this part we learn different types of Sorting Algorithms:
* Bogosort
* Selection Sort
* Quicksort
* Merge Sort

as well as the two most common types of searches:
* Linear Search
* Binary Search