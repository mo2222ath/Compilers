## Compilers Assignments

# Assignment 1

* Write a C++ code that does the following:
* You are not allowed to use any built-in functions except: <cstdlib>, <cstdio>, <cstring>, <iostream>.
* You are not allowed to use string class, vector, or anything from STL libraries.


* Modify the file CompilersTask_3_CodeGenerator.cpp to include a & operator, which is absoulte differenece, that is 3&5=2 5&3=2 ----- Done

* This operator has left associativity, and it has higher precedence than +,- and lower precedence than *,/ ------ Done

* Write an input tiny program and include it inside a comment, which contains several test cases (at least 20 statements involving operators) that explain its usage and proves correctness of using this operator with other operators. ------------ Done

* Half the mark is dedicatd to comments explaining the code before each code line (for only the part of the code which you added), test cases (at least 20 statements involving operators) that cover a lot of cases, and following the CodingStyle.pdf file. ------- Done

--------------------------------------------------------------------------------------------------

# Assignment 2

* Write a C++ code that does the following:
* You are not allowed to use any built-in functions except: <cstdlib>, <cstdio>, <cstring>, <iostream>.
* You are not allowed to use string class, vector, or anything from STL libraries.

* Modify the file CompilersTask_3_CodeGenerator.cpp to include 3 data types, int real bool -------- Done

* real should correspond to "double" in C++.
* All variables MUST be declared at the beginning of the program (example: int x;real y).
* It is possible to use boolean variable inside the if and repeat condition.

* It is not allowed to do arithmetic operations on boolean variables.
* It is allowed to do arithmetic operations on int, real variables such that, in the same expression, all variables are of the same type.
* It is not allowed to assign variables of different types.
* All cases not allowed above should produce meaningful compiler error message. You can use exceptions.

* If there is a case not mentioned above, just do whatever you believe it is meaningful.
* Write an input tiny program and include it inside a comment, which contains several test cases (at least 20 statements involving variables) that explain its usage and proves correctness of using variables.
* Half the mark is dedicatd to comments explaining the code before each code line (for only the part of the code which you added), test cases (at least 20 statements involving operators) that cover a lot of cases, and following the CodingStyle.pdf file.



# Assignment 3

* Write a C++ code that does the following:
* You are not allowed to use any built-in functions except: <cstdlib>, <cstdio>, <cstring>, <iostream>.
* You are not allowed to use string class, vector, or anything from STL libraries.

* Modify the file CompilersTask_3_CodeGenerator.cpp to include for loop, and break statement.  --- Done

* <forstmt> -> for <identifier> from <mathexpr> to <mathexpr> inc <mathexpr> startfor <stmtseq> endfor
* The initial value of the <identifier> is the value after "from", the loop will end if the value of <identifier> passes the value after "to".
* The value after "inc" can be positive or negative integer. It will be added to <identifier> at the end of each iteration.
* The following example sums all odd numbers starting from 1 to the minimum of 11 and n:

* sum:=0;
* for i from 1 to n inc 2
* startfor
* sum:=sum+i;
* if i=11 then break end
* endfor;

* write sum
* All parts of the code should work as expected, including RunProgram().
* All cases not allowed above should produce meaningful compiler error message. You can use exceptions.
* If there is a case not mentioned above, just do whatever you believe it is meaningful.

* Write an input tiny program and include it inside a comment, which contains several test cases (at least 10 loops involving positive and negative increments, nested loops, and involving break) that explain its usage and proves correctness of using loops.
* Half the mark is dedicated to comments explaining the code before each code line (for only the part of the code which you added), test cases that cover a lot of cases, and following the CodingStyle.pdf file.
