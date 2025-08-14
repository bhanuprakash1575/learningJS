
# what is variables?
- a variable is like a named storage box that holds data you can use and change while your program runs.

- let us suppose we know about console.log right, lets say our program is something similar to school.
    - our name is used in multiple places like in the attendence register, TC, admission book, and assume that there are so many places where our name is being used. 
    - at some point of time if we want to change our name form pooji to poojitha.
    - then we have change in all the places where older name is being used.
    - to tackle this problem we have variables.

- in programming point of view lets say our code is something like 
    ```
    console.log("my name is pooji.")
    console.log("pooji is studying b.tech")
    console.log("pooji is learning JS")
    .
    .
    99 similar statements
    .
    .
    console.log("pooji is a software engineer")
    ```
- in the above code we haven't used the variables. later, we decided to change the name from pooji to poojitha.
- to make this change, since we have almost 100 statement where pooji was being used, we have to change in all those places i.e., 100.

- Now we will see how we use variables to solve this
    ```
    let  name  = "pooji"


    console.log("my name is ",name)
    console.log(name," is studying b.tech")
    console.log(name," is learning JS")
    .
    .
    .
    99 more statements
    .
    .
    console.log(name," is a software engineer")
    ```
- now in the above code we have used the concept of variables to write our code.
- in order to change the name from pooji to poojitha we don't need to change the name in all the places instead if we can replace the following line 
    ```
    let name = "pooji" 
    ```
    - to 
    ```
    let name = "poojitha"
    ```
- since we are calling or using `name` variable everywhere which hold the actual value. changing it will be enough.

- #### THIS IS JUST AN EXAMPLE TO UNDERSTAND THE USECASE OF VARIABLES
- #### IT IS NOT ONLY RESTRICTED TO NAME YOU CAN USE IT FOR ANY VALUES WHICH NEEDS TO BE STORED AND REFERENCED AT MULTIPLE PLACES.
- #### SYNTAX for writing VARIABLES IN JS(other programming languages will have their own style or syntax for writing variables )
    ```
    variable_type<SPACE>variable_name;
    or
    variable_type<SPACE>variable_name=value
    ```
- you will learn about `variable_type` in the later part of the section



### THERE ARE 3 MAIN THING TO BE UNDERSTAND ABOUT VARIABLES

1. #### variable declaration
    ```
    let age;
    ```
2. #### variable assignment 
    -  (this means you are assinging some value to the variable)
    in the above line `name` is just declared it doesn't hold any value. you can assign some value to it like 
    ```
    age = 20
    ```
3. #### variable initialization(declaration+assignment)
```
let full_name = "Bhanu Prakash Reddy"
```

- YOU CAN JUST DECLARE A VARIABLE AND ASSIGN THE VALUE LATER OR DECLARE AND ASSIGN AT THE SAME PLACE DEPENDS ON USECASE.




# VARIABLE TYPES

1. ## let
    - variables declared with `let` type can be `changed` later. (similar to name example given above)
    ```
    let name = "Ramesh"
    name = "suresh" ✅
    ```

2. ## const
    - variables declared with `const` type `cannot be changed` after initialization.
    - `const` variables cannot be declared without assigment
    - `const` variables should always hold some value every time
    ```
    const name; ❌
    const age = 25 ✅
    age = 26 ❌
    ```

   
   
   
# There are some rules to declare the variable names, go through it.