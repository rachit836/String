

# **Experiment: Pointers in C++**

## **Aim : To study and implement pointer concepts in C++.**

## **Tools & Software Required : Programiz c++ compiler.**

---

### **Theory**

A **pointer** in C++ is a variable that stores the **memory address** of another variable. Pointers allow direct access and manipulation of memory, making them powerful for efficient data handling.

* **Declaration:**
  A pointer is declared using the `*` operator.
  Example:

  ```cpp
  int *ptr;
  ```

* **Dereferencing:**
  Accessing or modifying the value at the memory address using the `*` operator.

* **Pointer Arithmetic:**
  Incrementing/decrementing a pointer changes its address based on the data type size (e.g., `int` pointer + 1 moves 4 bytes forward on most systems).

* **Applications:**

  * Storing addresses of variables
  * Array traversal and manipulation
  * String handling
  * Dynamic memory allocation
  * Function arguments (call by reference)

---

### **Programs Implemented**

#### **1. Pointer Increment Demonstration**

**Logic:**
Demonstrates how pointer arithmetic works in C++. When incremented, a pointer moves forward by the size of its data type.

**Algorithm:**

1. Start.
2. Declare variables of type `int`, `float`, `double`, and `bool`.
3. Create pointers pointing to each variable.
4. Display addresses before increment.
5. Increment each pointer.
6. Display addresses after increment.
7. Stop.

---

#### **2. Sum and Difference Using Pointers**

**Logic:**
Stores array element addresses in a pointer array. Calculates the sum of all elements and finds the difference between two specific elements using pointers.

**Algorithm:**

1. Start.
2. Declare an integer array of size 5.
3. Create an array of integer pointers.
4. Assign addresses of array elements to the pointer array.
5. Initialize `sum = 0`.
6. Loop to add dereferenced values to sum.
7. Calculate the difference between element 4 and element 2 using pointers.
8. Print results.
9. Stop.

---

#### **3. Array Traversal and Reverse Using Pointers**

**Logic:**
Accesses array elements through pointers to print in normal and reverse order.

**Algorithm:**

1. Start.
2. Declare an integer array of 5 elements.
3. Create an array of integer pointers and assign each element’s address.
4. Loop forward to print elements.
5. Loop backward to print elements in reverse order.
6. Stop.

---

#### **4. String Operations Using Pointers**

**Logic:**
Reads a string, copies it using pointers, reverses it, and checks if it is a palindrome.

**Algorithm:**

1. Start.
2. Take string input from user.
3. Create a character array `str2` and a pointer to the first character of `str1`.
4. Copy characters from `str1` to `str2` using pointer arithmetic.
5. Reverse the string into `str2` using pointer traversal.
6. Compare original and reversed strings.
7. Print whether palindrome or not.
8. Stop.

---

### **Conclusion**

In this experiment, we learned:

* How to store and access memory addresses using pointers.
* How pointer arithmetic works for different data types.
* How to use pointers for array traversal, sum/difference calculation, and string operations.
* Practical applications of pointers in manipulating data efficiently and understanding memory handling in C++.

---

