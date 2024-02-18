directory 

13.4.1 what is binary search? 

13.4.2 algorithm implementation 

Learn Python 13.4.3 System 

##  13.4.1 what is binary search? 

We have already learned about dictionaries and collections in Python, and it is very convenient to use dictionaries and collections to achieve fast lookup. Dictionaries and collections use the index structure of hash tables to speed up lookup. How can we optimize lookup performance for sequential table structures such as lists? In this tutorial, we will learn about a very classic lookup algorithm in the course of Data Structures and Algorithms: Binary Search. 

>  Using binary lookup can greatly improve the lookup performance of sequential tables. 

The core principle of binary search: first sort the data set, and then compare it with the elements in the middle every time. If it is equal, it will be returned directly, and if it is not equal, it will find the other half of the interval according to the ascending or descending order of the data set. The search process of binary search is shown in the following figure: 

![avatar]( 13cc971efc7dd10f9dbe55af95d4455c.jpeg) 

>  (1) First compare the middle elements, 11 is larger than 7. Since the data set is in ascending order, look for the right interval next time

(2) Repeat this process until all searches are completed 

##  13.4.2 algorithm implementation 

We shall now implement this binary search algorithm: 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574577247
 ```  
##  Learn Python 13.4.3 System 

>  About the French fries teacher: Senior technical expert, technical writer, author of "Python Zero Basic Introduction Guide", "Java Zero Basic Introduction Guide" and other technical tutorials. French fries teacher's blog: http://www.chipscoco.com, system learning backend, crawler, data analytics, machine learning, quantitative investment. 

