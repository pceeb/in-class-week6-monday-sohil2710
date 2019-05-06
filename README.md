## In class exercise

**To submit your answers go to the following repository**

Scripts usually start out working well for a certain task and then get repurposed
for other task. In our case, the script works fine if there is one header
line in the input files, but if will fail or generate contaminated data if there are
additional lines. The number of header lines allowed in our program is indicated only in
one place.

1. If you wanted to reuse this program for a file that had 17 headers lines. What line of code
would you change in our program?

        Write the line of code that you will replace here:__

        What will be the new code?

        Write the new code here:___

2. would happen if we don’t included `import sys` in our program?

        Write you answer here:___

3. Let’s suppose that the third file that the user provides as input
has only one column. What error message will be generated?

        Write you answer here:___

4. Our program split lines of input files (except the first file) into elements
that are tab delimitated. However, data could be split by `,` or many other
characters. In this case is a good idea to define a new variable that takes the delimiter
provide by the user. Using what you learn about `sys.argv` in this class`.
Write a variable that reads a delimiter (e.g ',') provided as the first input file.

        Write your code here:__
