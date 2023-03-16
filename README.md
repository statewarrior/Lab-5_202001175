## <pre>             IT 314 - Software Engineering </pre> 
### Lab 5 : Static Analysis
### Student Name : ANKIT LOCHAN
### Student ID: 202001175

####  selected tool and github repo

Will be using pylint tool for python.<br/>
Github repo : https://github.com/rishabh1005/Algorithmic-Toolbox
<br/><br/>
![image](https://user-images.githubusercontent.com/124247870/225575119-c5a10a69-531c-4b2a-b912-aafa33568ac3.png)

#### Performing static Analysis and error understanding
1.https://github.com/rishabh1005/Algorithmic-Toolbox/blob/master/week6_dynamic_programming2/1_maximum_amount_of_gold/knapsack.py
<br/>Tool output: 
![image](https://user-images.githubusercontent.com/124247870/225579015-91df3ba6-c0e6-43f6-a48b-dd1007672bea.png)

2.https://github.com/rishabh1005/Algorithmic-Toolbox/blob/master/week6_dynamic_programming2/2_partitioning_souvenirs/partition3.py
<br/>Tool output: 
![image](https://user-images.githubusercontent.com/124247870/225579190-f79e042b-1ed3-47a3-8718-54530aa1db54.png)

3.https://github.com/rishabh1005/Algorithmic-Toolbox/blob/master/week1_programming_challenges/1_sum_of_two_digits/APlusB.py
<br/>Tool output: 
![image](https://user-images.githubusercontent.com/124247870/225579850-5e2f3ac2-b863-432d-af33-15cb0dc514e5.png)

4.https://github.com/rishabh1005/Algorithmic-Toolbox/blob/master/week1_programming_challenges/2_maximum_pairwise_product/max_pairwise_product.py
<br/>Tool output: 
![image](https://user-images.githubusercontent.com/124247870/225579972-0a71c856-89ee-417e-80d3-7b035c3082c6.png)

5.https://github.com/rishabh1005/Algorithmic-Toolbox/blob/master/week2_algorithmic_warmup/1_fibonacci_number/fibonacci.py
<br/>Tool output: 
![image](https://user-images.githubusercontent.com/124247870/225580063-e98f2ac2-eb87-4bf4-bd39-c6ad1bb2471a.png)


#### Understanding of errors: 
1) Missing module docstring/function docstring (C0114/C0ll6)
This indicates that neither the modules nor the functions have a docstring given. The docstring functions as a kind of comment or text description that the compiler ignores but which aids in explaining the function's or module's intended use to others. Writing docstrings is a wise move.
2) Variable does not match the snake case naming style, C0103
The declared variable is not named using the snake case convention, as indicated by this error.
3) Redefinition of the name from outerscope, W0621
This error indicates that a global variable with the same name as a local variable. By doing this, the global version of the variable is hidden and the local scope is changed to use the local version of the variable.
  4) Several statements on a single line, C0321
This indicates that a line has many statements. This is not a good practise because lines with only one statement will make the code easier to read.
  5) R1705: After return statement, unnecessary else
    This occurs when an else statement is added behind a "return" statement that is never actually executed.
  6) W0611: Imports not utilised When any modules or packages are imported but not used, this results.
  
    7)C0303: A line's last character is a trailing whitespace
       This occurs when there is an empty space before a new line and at the end of a line.
       This area is not required.


