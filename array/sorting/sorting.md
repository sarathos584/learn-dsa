#Sorting Algorithms

1. *What is sorting algorithms?*

A Sorting Algorithm is used to rearrange a given array or list of elements according to a comparison operator on the elements. The comparison operator is used to decide the new order of elements in the respective data structure.

Example: The most common sorting we have been used from school time would be making numbers in ascending/descending order. In programming, there are also questions like we will be given some array containing integers in a random order (sample: [2,1,7,4,0]), with the problem statement may be like we need to rearrange the given array in ascending order. So the output will be [0,1,2,4,7].

2. *Why there are different algorithms for sorting?*

From first question, you have already know what sorting algorithms are.There are different ways to sort a given array (if you already know time complexity and space complexity, you should know why there are different algos). Even though there are many, we need to select the best one for better performance both in case of run time and memory usage in the program. The selection of algo may depend on the input size ( think it as the number of elements in the given array for sorting)

 <!-- query section will be updated accordingly! -->

#Some useful sorting algos we are discussing

1. *Selection sort* 

     - Selection sort is a simple and efficient sorting algorithm that works by repeatedly selecting the smallest (or largest) element from the unsorted portion of the list and moving it to the sorted portion of the list. 
     The algorithm repeatedly selects the smallest (or largest) element from the unsorted portion of the list and swaps it with the first element of the unsorted part. This process is repeated for the remaining unsorted portion until the entire list is sorted.

     In simple words, in this algo, we first traverse through all elements in the array starting from 0th index to the last index. along with the iteration, we will be checking the condition which is the smallest/largest (not in every case, here we assuming we are told to sort the array in ascending/descending order), and making it the first element of the result array. After successful completion of first iteration, we can 