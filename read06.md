# read06
# function 
# WHAT IS A FUNCTION?
**Functions let you group a series of statements together to perform a specific task**
# declering a function
* function declaration to include the formal parameters. For example, if the my_function() function, discussed in the previous section, requires two integer parameters, the declaration could be expressed as follows:
return_type my_function(int x, y);where int x, y indicates that the function requires two parameters, both of which are integers. Note that the variable names x and y are optional, formal parameters. The actual parameter names in the function definition and subsequent calls need not be the same; only the types must match. Using meaningful formal parameter names is helpful in documenting the functionality.Because the declaration includes parameters, the compiler can check whether calls to this function are made properly
# Syntax
**function name([param[, param,[..., param]]]) {
   [statements]}**
   # calling function
   **While creating a C function, you give a definition of what the function has to do. To use a function, you will have to call that function to perform the defined task.
When a program calls a function, the program control is transferred to the called function. A called function performs a defined task and when its return statement is executed or when its function-ending closing brace is reached, it returns the program control back to the main program.To call a function, you simply need to pass the required parameters along with the function name, and if the function returns a value, then you can store the returned value**
![GitHub Logo](https://startingelectronics.org/software/arduino/learn-to-program-course/15-functions/functions2.png)


