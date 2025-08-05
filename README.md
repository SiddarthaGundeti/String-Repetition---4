# String-Repetition---4

You are given a string. Repeat the same string N times separated by space.

For example, if the string is messages and N = 3, the output should be messages messages messages.

Input: messages
3

Output: messages messages messages

Approach
To solve this problem, we will follow these steps:

Read the input string and the number N.

Create a new string by repeating the input string N times separated by space.
Print the new string.

Step-by-Step Explanation

Step 1: Read the input

First, we need to read the input string and the number N. We can use the input() function to read the input and int() to convert N into an integer.
 
Step 2: Create the new string

Now, we need to create a new string by repeating the input string N times separated by space. We can do this using the following code:
 
Here, we are adding the input string word to itself n - 1 times, with a space in between each repetition.

Step 3: Print the new string

Finally, we need to print the new string. We can do this using the print() function:
