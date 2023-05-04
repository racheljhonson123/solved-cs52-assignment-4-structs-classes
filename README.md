Download Link: https://assignmentchef.com/product/solved-cs52-assignment-4-structs-classes
<br>
<h1></h1>

Write a comment at the top that contains the following information

<strong>// Your Name</strong>

// CS 52 // Assignment #4

<ol start="2">

 <li>Properly indent, format and comment your code as necessary<span style="font-size: 2em;">                             Recursion                                                                   </span></li>

</ol>

Implement a program that lets the user enter a number and then prints the result calculated by the following function. Write a recursive function that n * n/3 * n/9 * …. where n/x &gt; 0 and <em>n</em> is a nonnegative integer. For example:

<strong>                        </strong>27: 27 * 9 * 3 * 1 = 729

8: 8 * 2 = 16

100: 100 * 33 * 11 * 3 * 1 = 108900

The function prototype should be: int recursive(unsigned int n);

Example:

<strong>             </strong>Input: <strong>27</strong>

Result: 729

<strong> </strong>Problem 2                               Date Class

<strong> </strong>Design a class called Date. The class should store a date in three integers month, day, and year. Declare all member variables private and all member functions public. Each instance variable should have getter and setter functions to get and set each value. There should be three member functions to print the date in the following forms:

Implement a program that lets the user enter a date using your Date class. The user enters a day, month and year. You will then create an object of the Date class passing in the three values to the constructor. Call each function to print the three different date forms as shown above.

<strong> </strong>

<strong> </strong>Problem 3                               structs




Create a <em>struct</em> called Employee. The <em>struct</em> should have the following members:

<ul>

 <li>firstName: <strong>string</strong></li>

 <li>lastName: <strong>string</strong></li>

 <li>pay: <strong>int</strong></li>

</ul>

Create a dynamic array of <em>n</em> employee variables where n is a number entered by the user. Then loop through the array and let the user input the data for each employee. Create a function that expects a pointer to the array as input and prints the elements in the array. Remember that arrays are <em>passed by reference,</em> that is, any modifications inside the function will be reflected in the caller’s array.

Example:         Number of employees: <strong>2</strong>

Employee 1

First Name: <strong>Allen</strong>

Last Name: <strong>Harper</strong>

Pay: <strong>1000</strong>

Employee 2

First Name: <strong>John</strong>

Last Name: <strong>Doe</strong>    Pay: <strong>500</strong>

Employees:

Name: Allen Harper (1000)

Name: John Doe (500)





