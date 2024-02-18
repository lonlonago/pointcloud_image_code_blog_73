directory 

7.2.1 calculate the second largest of the four 

7.2.2 use loops to calculate minor values 

Learn Python 7.2.3 System 

##  7.2.1 calculate the second largest of the four 

If there are four integer variables, how can we calculate the next largest value among them? 

![avatar]( be6571a9996b6f5e1d897a2abc9e514e.png) 

>  It is not difficult for beginners to solve this problem, but writing code in a concise and elegant manner is no small challenge. 

Directly comparing them one by one through if, this idea is obviously wrong, and the end result is just a long and smelly piece of code. A better idea is to calculate the maximum and median values of the three variables first, and determine their size relationship: 

![avatar]( 3548f706f830a9ab75891480e3f7e129.png) 

Then compare the fourth variable with the maximum value and the median value respectively. If it is larger than the maximum value of the three, then the second largest value must be the maximum value of the three. If it is smaller than the maximum value but larger than the median value, then the second largest value must be the fourth value. Otherwise, the second largest value must be the median value of the three. Why? Because the second largest value must not be the smallest value of the three, it can only be the median value of the three. 

>  First determine the size relationship between the three variables, so that it is convenient to compare. 

Code example: 

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574535174
 ```  
##  7.2.3 use loops to calculate minor values 

The logic of computing the minimum value in a for loop is simple. If you need to calculate the next smallest value, how do you do it? 

>  Many beginners think this problem is too complex, and they need to learn to simplify the complex problem in order to better understand the essence of things. 

The problem can be simplified to that the loop is executed only twice: if the first traversal results in a value smaller than the minimum, then the minimum is updated. If the second traversal results in a value smaller than the minimum, then the next smallest value must be the last minimum. 

>  In the process of implementation, it is also necessary to pay attention to the case where the traversed value is greater than the minimum value and less than the next smallest value, as well as the special case where the minimum value and the second smallest value are just the minimum value when initialized. 

Code example:  

Python 

 ```python  
After clicking on the GitHub Sponsor button above, you will obtain access permissions to my private code repository ( https://github.com/slowlon/my_code_bar ) to view this blog code. By searching the code number of this blog, you can find the code you need, code number is: 2024020309574535174
 ```  
##  Learn Python 7.2.3 System 

>  Fries Teacher Profile: Senior technical expert, technical writer, author of "Python Zero Basic Introduction Guide", "Java Zero Basic Introduction Guide" and other technical tutorials. Fries Teacher's blog: http://www.chipscoco.com, system learning backend, crawler, data analytics, machine learning 

