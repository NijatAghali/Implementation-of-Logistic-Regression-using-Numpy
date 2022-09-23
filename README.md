# Implementation-of-Logistic-Regression-using-Numpy

In this assignment, we will use a student exams results dataset (exams.csv). It is a collection of exam scores and a binary value indicating whether the student has passed the course. We will need to read the data from data file (exams.csv). It contains three columns. 
First two columns (exam_1, exam_2) are exam scores of a student and the third value indicates whether the student has passed the course or not (1 or 0). </br>
It is recommended to normalize the data at this stage. Gradient descent algorithm performs much better when the data is normalized. Use min-max normalization.

#### Steps of Implementation Logistic Regression from scratch (using numpy)

1) Normalize data using Z score normalization (recommended). </br>

2) Calculate cost function. Implement a function which returns cost given true y values, x values and parameters (w) </br>
![alt text](https://github.com/NijatAghali/Implementation-of-Logistic-Regression-using-Numpy/blob/master/Images/cost.png "Logo Title Text 1")

3) Implement gradient descent algorithm to minimize the cost function. </br>
![alt text](https://github.com/NijatAghali/Implementation-of-Logistic-Regression-using-Numpy/blob/master/Images/gradient.png "Logo Title Text 1")
