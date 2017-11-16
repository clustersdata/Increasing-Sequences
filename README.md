# Increasing-Sequences

Increasing Sequences

Description

Given a string of digits, insert commas to create a sequence of strictly increasing numbers so as to minimize the magnitude of the last number. For this problem, leading zeros are allowed in front of a number.

Input

Input will consist of multiple test cases. Each case will consist of one line, containing a string of digits of maximum length 80. A line consisting of a single 0 terminates input.

Output

For each instance, output the comma separated strictly increasing sequence, with no spaces between commas or numbers. If there are several such sequences, pick the one which has the largest first value;if there's a tie, the largest second number, etc.

Sample Input

3456
3546
3526
0001
100000101
0

Sample Output

3,4,5,6
35,46
3,5,26
0001
100,000101
