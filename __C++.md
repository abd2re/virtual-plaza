# Variable types
-   `int` - stores integers (whole numbers), without decimals, such as 123 or -123
-   `double` - stores floating point numbers, with decimals, such as 19.99 or -19.99
-   `char` - stores single characters, such as 'a' or 'B'. Char values are surrounded by single quotes
-   `string` - stores text, such as "Hello World". String values are surrounded by double quotes
-   `bool` - stores values with two states: true or false
---
- A floating point number can also be a scientific number with an "e" to indicate the power of 10:
```c++
float f1 = 35e3;  
double d1 = 12E4;  
cout << f1;  
cout << d1;
```
---
- you can use ASCII values to display certain characters:
```c++
char a = 65, b = 66, c = 67;  
cout << a;  
cout << b;  
cout << c;
```
--- 
Logical operators are used to determine the logic between variables or values:
&&  = Logical and
||  = Logical or
! = Logical not
***
However, `cin` considers a space (whitespace, tabs, etc) as a terminating character, which means that it can only display a single word (even if you type many words):
That's why, when working with strings, we often use the `getline()` function to read a line of text. It takes `cin` as the first parameter, and the string variable as second:
```c++
string fullName;  
cout << "Type your full name: ";  
getline (cin, fullName);  
cout << "Your name is: " << fullName;  
  
// Type your full name: John Doe  
// Your name is: John Doe
```
--- 
Other functions, such as `sqrt` (square root), `round` (rounds a number) and `log` (natural logarithm), can be found in the `<cmath>` header file:
```c++
// Include the cmath library  
#include <cmath>  
  
cout << sqrt(64);  
cout << round(2.6);  
cout << log(2);
```
--- 
A boolean variable is declared with the `bool` keyword and can only take the values `true` or `false`:
```c++
bool isCodingFun = true;  
bool isFishTasty = false;  
cout << isCodingFun;  // Outputs 1 (true)  
cout << isFishTasty;  // Outputs 0 (false)
```
--- 
There is also a short-hand if else, which is known as the **ternary operator** because it consists of three operands. It can be used to replace multiple lines of code with a single line. It is often used to replace simple if else statements:
Instead of writing:
```c++
int time = 20;  
if (time < 18) {  
  cout << "Good day.";  
} else {  
  cout << "Good evening.";  
}
```
You can simply write:
```c++
int time = 20;  
string result = (time < 18) ? "Good day." : "Good evening.";  
cout << result;
```
--- 
## C++ Switch Statements
Use the `switch` statement to select one of many code blocks to be executed.
```c++
switch(_expression_) {  
  case x:  
    _// code block_  
    break;  
  case y:  
    _// code block_  
    break;  
  default:  
    _// code block_  
}
```
---
## The Do/While Loop

The `do/while` loop is a variant of the `while` loop. This loop will execute the code block once, before checking if the condition is true, then it will repeat the loop as long as the condition is true.
```c++
do {  
  _// code block to be executed_
}  
while (_condition_);
```
The example below uses a `do/while` loop. The loop will always be executed at least once, even if the condition is false, because the code block is executed before the condition is tested:
```c++
int i = 0;  
do {  
  cout << i << "\n";  
  i++;  
}  
while (i < 5);
```
---
## C++ For Loop

When you know exactly how many times you want to loop through a block of code, use the `for` loop instead of a `while` loop:
```c++
for (_statement 1_; _statement 2_; _statement 3_) {  
  _// code block to be executed_  
}
```
**Statement 1** is executed (one time) before the execution of the code block.

**Statement 2** defines the condition for executing the code block.

**Statement 3** is executed (every time) after the code block has been executed.

The example below will print the numbers 0 to 4:
```c++
for (int i = 0; i < 5; i++) {  
  cout << i << "\n";  
}
```
#### Example explained

Statement 1 sets a variable before the loop starts (int i = 0).

Statement 2 defines the condition for the loop to run (i must be less than 5). If the condition is true, the loop will start over again, if it is false, the loop will end.

Statement 3 increases a value (i++) each time the code block in the loop has been executed.
***
## The foreach Loop
```c++
for (_type variableName_ : _arrayName_) {  
  // code block to be executed  
}
```
```c++
int myNumbers[5] = {10, 20, 30, 40, 50};  
for (int i : myNumbers) {  
  cout << i << "\n";  
}
```
---
## C++ Arrays

Arrays are used to store multiple values in a single variable, instead of declaring separate variables for each value.

To declare an array, define the variable type, specify the name of the array followed by **square brackets** and specify the number of elements it should store:
```c++
string cars[3] = {"Volvo", "BMW", "Ford"}; // Also three arrays
```
## Omit Array Size

In C++, you don't have to specify the size of the array. The compiler is smart enough to determine the size of the array based on the number of inserted values:
```c++
string cars[] = {"Volvo", "BMW", "Ford"}; // Three arrays
```
## Omit Elements on Declaration
```c++
string cars[5];  
cars[0] = "Volvo";  
cars[1] = "BMW";  
...
```
---
## C++ Structures

Structures (also called structs) are a way to group several related variables into one place. Each variable in the structure is known as a **member** of the structure.

Unlike an [array](https://www.w3schools.com/cpp/cpp_arrays.asp), a structure can contain many different data types (int, string, bool, etc.).

To create a structure, use the `struct` keyword and declare each of its members inside curly braces.

After the declaration, specify the name of the structure variable (**myStructure** in the example below):

```c++
struct {             // Structure declaration  
  int myNum;         // Member (int variable)  
  string myString;   // Member (string variable)  
} myStructure;       // Structure variable
```

```c++
// Create a structure variable called myStructure  
struct {  
  int myNum;  
  string myString;  
} myStructure;  
  
// Assign values to members of myStructure  
myStructure.myNum = 1;  
myStructure.myString = "Hello World!";  
  
// Print members of myStructure  
cout << myStructure.myNum << "\n";  
cout << myStructure.myString << "\n";
```

## One Structure in Multiple Variables

You can use a comma (`,`) to use one structure in many variables:
```c++
struct {  
  int myNum;  
  string myString;  
} myStruct1, myStruct2, myStruct3; // Multiple structure variables separated with commas
```

## Named Structures
By giving a name to the structure, you can treat it as a data type. This means that you can create variables with this structure anywhere in the program at any time.

To create a named structure, put the name of the structure right after the `struct` keyword:
```c++
struct myDataType { // This structure is named "myDataType"  
  int myNum;  
  string myString;  
};
```
To declare a variable that uses the structure, use the name of the structure as the data type of the variable:
```c++
myDataType myVar;
```
--- 
## Creating References

A reference variable is a "reference" to an existing variable, and it is created with the `&` operator:
```c++
string food = "Pizza";  // food variable  
string &meal = food;    // reference to food
```

```c++
string food = "Pizza";  
string &meal = food;  
  
cout << food << "\n";  // Outputs Pizza  
cout << meal << "\n";  // Outputs Pizza
```

In the example from the previous page, the `&` operator was used to create a reference variable. But it can also be used to get the memory address of a variable; which is the location of where the variable is stored on the computer.

When a variable is created in C++, a memory address is assigned to the variable. And when we assign a value to the variable, it is stored in this memory address.

To access it, use the `&` operator, and the result will represent where the variable is stored:
```c++
string food = "Pizza";  
  
cout << &food; // Outputs 0x6dfed4
```
---
# C++ Pointers
You learned from the previous chapter, that we can get the **memory address** of a variable by using the `&` operator:
```c++
string food = "Pizza"; // A food variable of type string  
  
cout << food;  // Outputs the value of food (Pizza)  
cout << &food; // Outputs the memory address of food (**0x6dfed4**)
```
A **pointer** however, is a variable that **stores the memory address as its value**.

A pointer variable points to a data type (like `int` or `string`) of the same type, and is created with the `*` operator. The address of the variable you're working with is assigned to the pointer:
```c++
string food = "Pizza";  // A food variable of type string  
string* ptr = &food;    // A pointer variable, with the name ptr, that stores the address of food  
  
// Output the value of food (Pizza)  
cout << food << "\n";  
  
// Output the memory address of food (0x6dfed4)  
cout << &food << "\n";  
  
// Output the memory address of food with the pointer (0x6dfed4)  
cout << ptr << "\n";
```
#### Example explained

Create a pointer variable with the name `ptr`, that **points to** a `string` variable, by using the asterisk sign `*` (`string* ptr`). Note that the type of the pointer has to match the type of the variable you're working with.

Use the `&` operator to store the memory address of the variable called `food`, and assign it to the pointer.

Now, `ptr` holds the value of `food`'s memory address.

## Get Memory Address and Value

In the example from the previous page, we used the pointer variable to get the memory address of a variable (used together with the `&` **reference** operator). However, you can also use the pointer to get the value of the variable, by using the `*` operator (the **dereference** operator):
```c++
string food = "Pizza";  // Variable declaration  
string* ptr = &food;    // Pointer declaration  
  
// Reference: Output the memory address of food with the pointer (0x6dfed4)  
cout << ptr << "\n";  
  
// Dereference: Output the value of food with the pointer (Pizza)  
cout << *ptr << "\n";
```

## Modify the Pointer Value

You can also change the pointer's value. But note that this will also change the value of the original variable:
```c++
string food = "Pizza";  
string* ptr = &food;  
  
// Output the value of food (Pizza)  
cout << food << "\n";  
  
// Output the memory address of food (0x6dfed4)  
cout << &food << "\n";  
  
// Access the memory address of food and output its value (Pizza)  
cout << *ptr << "\n";  
  
// Change the value of the pointer  
*ptr = "Hamburger";  
  
// Output the new value of the pointer (Hamburger)  
cout << *ptr << "\n";  
  
// Output the new value of the food variable (Hamburger)  
cout << food << "\n";
```
---
# C++ Functions
C++ provides some pre-defined functions, such as `main()`, which is used to execute code. But you can also create your own functions to perform certain actions.

To create (often referred to as _declare_) a function, specify the name of the function, followed by parentheses **()**:
```c++
void _myFunction_() {  
  // code to be executed  
}
```
-   `myFunction()` is the name of the function
-   `void` means that the function does not have a return value. You will learn more about return values later in the next chapter
-   inside the function (the body), add code that defines what the function should do
## Call a Function

Declared functions are not executed immediately. They are "saved for later use", and will be executed later, when they are called.

To call a function, write the function's name followed by two parentheses `()` and a semicolon `;`

In the following example, `myFunction()` is used to print a text (the action), when it is called:
```c++
// Create a function  
void myFunction() {  
  cout << "I just got executed!";  
}  
  
int main() {  
  myFunction(); // call the function  
  return 0;  
}  
  
// Outputs "I just got executed!"
```
**Note:** If a user-defined function, such as `myFunction()` is declared after the `main()` function, **an error will occur**.
## Default Parameter Value
---
## Call stack
![[image-20230326153440562.png]]



