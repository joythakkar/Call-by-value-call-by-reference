# Call-by-value-call-by-reference

# Function Calling Methods in C++

## 🎯 Aim
To study and implement different ways of calling functions in C++:
- Call by Value
- Call by Reference (using pointers)
- Pass by Reference (using references in C++)

---

## 📌 Objectives
- To understand how data is transferred between functions.  
- To differentiate between call by value, call by reference, and pass by reference.  
- To observe how changes inside a function affect or do not affect actual variables.  
- To develop a clear idea about memory management during function calls.  

---

## 📖 Theory
In programming, functions allow us to divide a large program into smaller, manageable blocks.  
When data is passed to a function, there are different ways in which it can be handled.  

### 🔹 Call by Value
- Copy of the actual parameter is passed.  
- Changes inside the function do **not** affect the original variable.  
- Example: swapping two numbers does not change the real values.  

### 🔹 Call by Reference (Pointers)
- Address of the variable is passed.  
- Function can directly modify original variables.  
- Requires careful pointer handling.  

### 🔹 Pass by Reference (References)
- Reference variable (alias) of actual variable is passed.  
- Safer and simpler than pointers.  
- Any change reflects directly on original variable.  

---

## 📊 Comparison Table

| Method             | What is Passed? | Changes Affect Original? | Memory Used | Ease of Use |
|--------------------|-----------------|--------------------------|-------------|-------------|
| Call by Value      | Copy of value   | ❌ No                    | More        | Very Safe   |
| Call by Reference  | Address         | ✅ Yes                   | Less        | Needs pointer care |
| Pass by Reference  | Reference       | ✅ Yes                   | Less        | Simple & Efficient |

---

SAMPLE OUTPUT:
          
          Pass by value code-
                        a is:5
                        b is:2
                        
          Pass by pointer:
                        Original value of a is:5
                        original value of b is:2
                        Swapped value of a is:2
                        Swapped value of b is:5 

          Call by reference:
                        Original value of a is:12
                        original value of b is:21
                        Swapped value of a is:21
                        Swapped value of b is:12

         Array modification:
                        Enter a number: 4
                        Before update: 10 20 30 40 50 
                        After update: 4 5 6 7 8 

        Salary increment using pointer:
                        Enter the number of recent projects: 7
                        How many research publications have you done? 5
                        How much profit have you made in last one year? 20k
                        Enter the number of new projects in pipeline: 
                        Sorry! You did not meet the selection criteria.


 CONCLUSION:
 -------------------------------------------------------------------------------
        This experiment helps in understanding how functions interact with variables
        through memory. Mastering pointer operations and the distinction between
        Call by Value and Call by Reference is essential for efficient programming,
        especially in systems programming, embedded systems, and performance-critical
        applications.


          
          
