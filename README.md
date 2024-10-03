# power-digit-sum
and the sum of its digits is .

What is the sum of the digits of the number  ?

Input Format

The first line contains an integer , i.e., number of test cases.
Next  lines will contain an integer .

Constraints

Output Format

Print the values corresponding to each test case.

Sample Input

3
3
4
7
Sample Output

8
7
11
Explanation

, sum of digits is .
, sum of digits is .
, sum of digits is .
--------------------------------------------------------------------------------------------------------
# Enter your code here. Read input from STDIN. Print output to STDOUT
for _ in range(int(input())):
    print(sum(int(c) for c in str(2 ** int(input()))))
