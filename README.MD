# Algorithms-DataStructure

This project consist of different sorthing algorithmn their time complexity and their comparision

#Description
This project is coded in java.

# Usage
In order to run this application you must do the following things installed on your machine:

    -Java 
    -IDE to run your application (preferably Eclipse).

#Overview:
Implemented the following sorting algorithms and compared them:

Insertion sort
Merge sort
Heapsort [vector based, and inserted one item at a time]
In-place quicksort (any random item or the first or the last item of the input can be pivot).
Modified quicksort
Used median-of-three as pivot.
For small sub-problem of size ≤ 10,  used insertion sort.

##Project folder layout

  -src
  
    -Default Package

    	-Java files

##Main Flow of Application
Sorting.java files holds main method which calls different sorting algorithms of different class files by creating objects.

	-Run sorting.java file to run the code 
	-User will be asked if they wanna input unsorted array, sorted array or reverse sorted array
	-Execution will then begin and print 3 iterations of each array data size i.e 20000, 30000, 40000, 50000, 60000.
	-Code will calculate average time of those 3 iterations and will dislay araay of the execution times.
