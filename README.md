# Bubble-sort

A Bubble sort is an easy algorithm among the various sorting algorithms.The bubble sort uses a straightforward logic that works by repeating swapping the adjacent elements if they are not in the right order. It compares one pair at a time and swaps if the first element is greater than the second element; otherwise, move further to the next pair of elements for comparison.

Example -

We are creating a list of element, which stores the integer numbers

list1 = [5, 3, 8, 6, 7, 2]

Here the algorithm sort the elements -

-----FIRST ITERATION-----

[5, 3, 8, 6, 7, 2]
It compares the first two elements and here 5>3 then swap with each other. Now we get new list is -

[3, 5, 8, 6, 7, 2]

In second comparison, 5 < 8 then swapping happen -

[3, 5, 8, 6, 7, 2]

In third comparison, 8>6 then swap -

[3, 5, 6, 8, 7, 2]

In fourth comparison, 8>7 then swap -

[3, 5, 6, 7, 8, 2]

In fifth comparison, 8>2 then swap-

[3, 5, 6, 7, 2, 8]

Here the first iteration is complete and we get the largest element at the end. Now we need to the len(list1) - 1

-----SECOND ITERATION-----

[3, 5, 6, 7, 2, 8] - > [3, 5, 6, 7, 2, 8] here, 3<5 then no swap taken place

[3, 5, 6, 7, 2, 8] - > [3, 5, 6, 7, 2, 8] here, 5<6 then no swap taken place

[3, 5, 6, 7, 2, 8] - > [3, 5, 6, 7, 2, 8] here, 6<7 then no swap taken place

[3, 5, 6, 7, 2, 8] - > [3, 5, 6, 2, 7, 8] here 7>2 then swap their position. Now

[3, 5, 6, 2, 7, 8] - > [3, 5, 6, 2, 7, 8] here 7<8 then no swap taken place.

-----THIRD ITERATION-----

[3, 5, 6, 2, 7, 8] - > [3, 5, 6, 7, 2, 8] here, 3<5 then no swap taken place

[3, 5, 6, 2, 7, 8] - > [3, 5, 6, 7, 2, 8] here, 5<6 then no swap taken place

[3, 5, 6, 2, 7, 8] - > [3, 5, 2, 6, 7, 8] here, 6<2 then swap their positions

[3, 5, 2, 6, 7, 8] - > [3, 5, 2, 6, 7, 8] here 6<7 then no swap taken place. Now

[3, 5, 2, 6, 7, 8] - > [3, 5, 2, 6, 7, 8] here 7<8 then swap their position.

It will iterate until the list is sorted.

-----FOURTH ITERATION-----

[3, 5, 2, 6, 7, 8] - > [3, 5, 2, 6, 7, 8]

[3, 5, 2, 6, 7, 8] - > [3, 2, 5, 6, 7, 8]

[3, 2, 5, 6, 7, 8] - > [3, 2, 5, 6, 7, 8]

[3, 2, 5, 6, 7, 8] - > [3, 2, 5, 6, 7, 8]

[3, 2, 5, 6, 7, 8] - > [3, 2, 5, 6, 7, 8]

-----FIFTH ITERATION------

[3, 2, 5, 6, 7, 8] - > [2, 3, 5, 6, 7, 8]
