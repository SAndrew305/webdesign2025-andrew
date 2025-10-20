## VARIABLES

### VARIABLE DECLARATIONS

To use variables in JS, you need to declare (or create) a variable, using one of the following keywords.

- let - Variable that can be reassigned or redeclared later
- const - a variable that cannot be reassigned or redeclared later
- var - a function/global scope value (deprecated)

### VARIABLE SCOPES

Scope - Visibility of a variable or how it can be used after declaration.

- Global Scope - Variables declared outside any function or curly braces '{}', and can be accessed from anywhere within the same Javascript code. All variables listed above provide this scope by default.

- Function Scope - Variables declared within a function can only be used within that same function. Outside that function, they are undefined. var, let and const all provide this Scope.

- Block Scope: A block is any part of JavaScript code bounded by '{}'. Variables declared within a block can not be accessed outside that block. This Scope is only provided by the let and const keywords. If you declare a variable within a block using the var keyword, it will NOT have Block Scope.

- Local Scope - Local variables are only recognized inside their functions, variables with the same name can be used in different functions. Local variables are created when a function starts, and deleted when the function is completed. var, let and const all provide this Scope.

## DATA TYPES

### PRIMITIVE

- String

- Undefined

- Number

- Boolean

- Null

### NON-PRIMITIVE

- Object

- "typeof" Operator
