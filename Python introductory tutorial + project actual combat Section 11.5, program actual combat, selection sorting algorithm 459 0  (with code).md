directory 

Introduction to 11.5.1 Sorting Algorithm 

11.5.2 selection sorting algorithm 

Learn Python 11.5.3 System 

##  Introduction to 11.5.1 Sorting Algorithm 

The so-called sorting refers to arranging the elements in the data collection in order from small to large, or in order from large to small. The former is called ascending sorting, and the latter is called descending sorting. In this course on Data Structures and Algorithms, we will learn many sorting-related algorithms, such as Bubble Sort Algorithm, Select Sort Algorithm, Quick Sort Algorithm, Heap Sort Algorithm, etc. In this tutorial, we will master the very classic Select Sort algorithm. 

##  11.5.2 selection sorting algorithm 

The core idea of selection sorting is to select the smallest (large) element from the data set, store it at the beginning of the interval, and then find the smallest (large) element from the remaining unsorted elements, put it at the end of the sorted interval, and repeat this process until sorting is achieved. The following figure shows the process of selecting the minimum value of 1 to the header of the interval: 

![avatar]( 4f63b42a9dc786f9e1a9700cac78fceb.png) 

>  (1) In the initial case, assume that the minimum value is 3 and the minimum index is 0.

(2) Compare element 3 with element 2, 2 is smaller than 3, and update the minimum index to index 1 of element 2.

(3) Compare the element 2 corresponding to index 1 with the 1 at the end, 1 is smaller than 2, and update the minimum index to index 2 of element 1.

(4) Minimum index 2 is not equal to the initial minimum index 0, so elements 3 and 1 are interchanged. 

According to the above principles, we now use the Python language to implement the selection sorting algorithm: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574519517
 ```  
##  Learn Python 11.5.3 System 

>  About the French fries teacher: Senior technical expert, technical writer, author of "Python Zero Basic Introduction Guide", "Java Zero Basic Introduction Guide" and other technical tutorials. French fries teacher's blog: http://www.chipscoco.com, system learning backend, crawler, data analytics, machine learning, quantitative investment. 

