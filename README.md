## In class exercise

1. If you wanted to reuse this program for a file that had 17 headers lines. What line of code
would you change in our program?

        Write the line of code that you will replace here:__ 
        
        Replace this line: if LineNumber > 0:

        What will be the new code? 
        
        We need to change the conditions of for-loop so that first 17 line are ignored for this purpose

        Write the new code here:___ 
        
        Replace with: if LineNumber > 16:

2. would happen if we don’t included `import sys` in our program?

        Write you answer here:___ 
        
        In python user inputs are accessed through the sys module by using sys.argv as variable

3. Let’s suppose that the third file that the user provides as input
has only one column. What error message will be generated?

        Write you answer here:___ 
        
        Error message generated: Line 1 not XY format in file LEDRed.txt

4. Our program split lines of input files (except the first file) into elements
that are tab delimitated. However, data could be split by `,` or many other
characters. In this case is a good idea to define a new variable that takes the delimiter
provide by the user. Using what you learn about `sys.argv` in this class`.
Write a variable that reads a delimiter (e.g ',') provided as the first input file.

        Write your code here:__ I am unsure about this Daniel
        
        FileDelimiter= sys.argv[1:]
