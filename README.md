Download Link: https://assignmentchef.com/product/solved-csl101-assignment-1
<br>



<ol>

 <li>Write a C program that calculates the HCF and LCM of two numbers.</li>

 <li>Write a C program to display and find the sum of the series 1+11+111+….111 upto n. For eg. if n=4, the series is : 1+11+111+1111. Take the value of ‘n’ as input from the user.</li>

 <li>Amicable numbers are found in pairs. A given pair of numbers is Amicable if the sum of the proper divisors (not including itself) of one number is equal to the other number and vice – versa. For example 220 &amp; 284 are amicable numbers First we find the proper divisors of 220:</li>

</ol>

220:1, 2, 4, 5, 10, 11, 20, 22, 44, 55, 110

1+ 2 + 4 + 5 + 10 + 11 + 20 + 22 + 44 + 55 + 110 = 284

Now, 284: 1, 2, 4, 71, 142

1 + 2 + 4 + 71 + 142 = 220

Write a C program to check that the input pair of numbers is amicable.

<ol start="4">

 <li>A triangular number is one which can be represented by that number of pebbles in a symmetric triangle. The first five triangular numbers are 1, 3, 6, 10 and 15.</li>

</ol>

Write a C function ”int isTriangular(int n)” to test if a number ‘n’ is triangular or not. It should return 1 if it is triangular and 0 if not.

T1=1 T2=3 T3=6 T4=10 T5=15

<ol start="5">

 <li>Write a C program to input n numbers in an array, calculate the sum of all even numbers and all odd numbers in the array and print the larger sum.</li>

</ol>

Example:

If the array contains the following elements:

2, 3, 3, 5, 4, 8, 7, 11, 2

The sum of all even elements is 2+4+8+2=16 Sum of all odd elements is 3+3+5+7+11=29 Therefore, the output should be 29.

<ol start="6">

 <li>Write a C program to calculate the volume of the following shapes: Cube, Cuboid, Sphere, Cylinder and Cone. Ask the user which one s/he wants to calculate, and take the appropriate required inputs. Then print the result. The input should be taken in the main function and calculations for every solid should be done in a separate function by passing appropriate arguments.</li>

</ol>

Example:

If the user chooses the option for cube, only one input is required i.e., the side. The volume is then calculated and printed.

If the user chooses the option for cuboid, only three inputs are required i.e., length, breadth and height. The volume is then calculated and printed.

<ol start="7">

 <li>Write a C program to check if a number has three consecutive 5s. If yes, print YES, else print NO.</li>

</ol>

Example:

Number: 1353554

Result: NO

Number: 345559

Result: YES

<ol start="8">

 <li>Write a C program to accept 10 values in an integer array. Display the number of odd, even and negative numbers.</li>

 <li>Write a C program to accept the basic salary of an employee from the user. Calculate the gross Salary on the following basis:</li>

</ol>

Basic                             HRA  DA

1 – 4000                       10%     50%

4001 – 8000                 20%     60%

8001 – 12000                25%     70%

12000 and above          30%     80%

<ol start="10">

 <li>Write a C function celsius() to convert degrees Fahrenheit to degrees Celsius. (The conversion formula is °C = 5/9 * (°F – 32).) Use it to print a Fahrenheit-to-Centigrade table for -40 to 220 degrees Fahrenheit, in increments of 10 degrees. (Remember that %f is the printf format to use for printing floating-point numbers. Also, remember that the integer expression 5/9 gives 0, so you won’t want to use integer division.)</li>

 <li>An Electricity board charges the following rates for use of electricity.</li>

</ol>

For the First 200 units : Rs 1 per unit For the next 100 units : Rs 1.5 per unit Beyond 300 units : Rs 2 Per unit.

Write a C Program to read no of unit consumed and print out total charge amount.

<ol start="12">

 <li>Write a C program, which will print two digit numbers whose sum of both digit is multiple of seven.</li>

</ol>

e.g. 16,25,34……

<ol start="13">

 <li>Write a C program that take 2 integer sets A[] and b[] as input and prints results of following</li>

</ol>

set operations:

<ol>

 <li>A union B (Write function set_union()) ii. A intersection B (Write function set_intersection()) iii. A-B and B-A (Write function set_difference())</li>

 <li>Write a C program to take a list of n elements from the user. Store it in an array. Reverse the elements of array list and print the same.</li>

</ol>




<ol start="14">

 <li>Input size and values in two arrays A and B, of max size 100. Then, compute A[i]+B[i] and store in array C. And compute A[i]*B[i] and store in array D.</li>

</ol>




<ol start="16">

 <li>Input date, month and year from the user, and using switch case, display in worded format. e.g.</li>

</ol>

input: d=16, m=7, y=1992 output: 16th July, 1992




<ol start="17">

 <li>Write a C program to print the following pattern:</li>

 <li>a) 1                                         b) 1</li>

</ol>

1 2                                          2 2

1 2 3                                         3 3 3

1 2 3 4                                      4 4 4 4

1 2 3 4 5                                  5 5 5 5 5




<ol start="18">

 <li>Write a C program, That reads list of n integer and print sum of product of consecutive</li>

</ol>

numbers.

if n=7 and numbers are 4,5,2,5,6,4,7 then output is 4*5+5*2+2*5+5*6+6*4+4*7 = 122.

<ol start="19">

 <li>Find out the ugly prime number</li>

</ol>

Desc: The given number is ugly prime number if it’s prime factor contains only among 2,3 or 5.

e.g. 20= 2*2*5 is ugly prime number

14=2*7 is not a ugly prime number

So write a C program which takes values from 1 to n and returns the number of ugly primes number in it.

input: 20 output: 3

<ol start="20">

 <li>Write 2 different C functions to compute area and perimeter of a triangle whose sides a, b, and c are given by user as inputs. Formula to compute perimeter = a + b + c</li>

</ol>

Formula to compute area = [s(s-a)(s-b)(s-c)]0.5 Where s = 0.5 * (a+b+c) Function prototypes are:

double perim(double a, double b, double c) double area(double a, double b, double c)





