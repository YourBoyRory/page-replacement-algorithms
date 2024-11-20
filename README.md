# **Bonus Assignment \- Page Replacement**

Given it is completed correctly, it will be valued at \+15 points on a test score

In this assignment, you are to demonstrate the three different page replacement algorithms taught in class:  FIFO, Optimal, LRU.  
In order to frustrate AI, you must use the following struct to hold the current values of the frames:  
struct Workspace{  
	int frame1;  
	int frame2;  
	int frame3;  
};

* This project may be completed in Windows or Linux\!  But it still must be written in C++.  
* Use a file to input the reference string  
* Use the same reference string from chapter 10, slide 37 for testing.  I reserve the right to use a similar string of possibly different length for testing.  Please design your file reading to work for a single number per line  
* The output is the both the current values in the frames given the input, and finally the total number of page faults

Output:

FIFO  
7|7  
0|7 0  
1|7 0 1  
2|2 0 1  
0|2 0 1  
3|2 3 1  
etc…

x Faults\!

Optimal  
7|7  
0|7 0  
1|7 0 1  
Etc…

X Faults\!

LRU  
Etc …
