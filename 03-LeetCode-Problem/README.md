03 leetcode problem

In this challenge, you need to calculate and print the sum of elements in an array, considering that some integers may be very large.

Function Description
Complete the aVeryBigSum function with the following parameter(s):
int ar[n]: an array of integers

Return
long: the sum of the array elements

Input Format
The first line of the input consists of an integer.
The next line contains space-separated integers contained in the array.

Output Format
Return the integer sum of the elements in the array.

Constraints
1 ≤ n ≤ 10
0 ≤ ar[i] ≤ 10

Sample Input
STDIN                                                   Function
-----                                                   --------
5                                                       arr[] size n = 5
1000000001 1000000002 1000000003 1000000004 1000000005  arr[...]  

Output
5000000015

Note:
The range of the 32-bit integer is 
(−2³¹) to (2³¹ - 1) or [-2147483648, 2147483647]

When we add several integer values, the resulting sum might exceed the above range. You might need to use long int C/C++/Java to store such sums.