# Kaprekar-Number

Filter out the Kaprekar Numbers 

A Kaprekar number consists of n digits which, when squared and split up into two parts with the left part having either n or n-1 digits and the right part having exactly n digits with both the sides as non-zero, and when those left and right parts are added together gives the original number. For example, let us take 45. When squared, it gives us 2025, and when we split 2025 and sum up, it gives 45 (20+25). So, 45 is a Kaprekar number. You will be given a list of strings consists of integers. You should use the java8 stream, map, and filter functions to store only the Kaprekar numbers in a list and return that. 


Input Specifications: A list of strings 

Output Specifications: A list of Kaprekar numbers from the input list (The list should be of long type). 

Sample Input 1: "93", "94", "95", "96", "97", "98", "99", "1001 

Sample Output 1: [1, 9, 45, 55, 99] 
