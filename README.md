# Base K Adder

## Due: Fri 1/26 at 11:59 PM

- Create a program called `BaseKAdder.java`
- Write a function to check if a number is valid given a base
- Write a function to convert a number from base 10 to a given base
- Write a function to convert a number from a given base to base 10
- In the main method:
  - Prompt the user for an integer
    - This will be the base of the next two number
    - It can be any value greater than 0 and less than or equal to 20
  - Prompt the user for two integers
    - These will be the numbers you need to add together
    - Print an error message if either number given is not a valid number for the given base and stop the program
  - Print the sum of the two integers in the base that was given

***Example Input:***\
8\
173\
147\
***Example Output:***\
The sum of the base 8 numbers 173 and 147 is 342\
\
***Example Input:***\
12\
4D\
3A\
***Example Output:***\
ERROR: Invalid number given, 4D cannot be a base 12 number
