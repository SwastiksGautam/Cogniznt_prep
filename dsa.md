---
aliases:
  - "[[cognizant]]"
---
# **1. Coding – Java Programming**

### 🔹 Problem Solving

- Writing algorithms and logic to solve problems.
    
- Example: Find the largest number in an array, reverse a string, implement factorial, etc.
    

### 🔹 Condition Statements

- **if, if-else, nested if, switch** → Used to control decision-making in a program.
    

`if(num > 0) System.out.println("Positive"); else System.out.println("Negative");`

### 🔹 Control Flow Statements

- **Loops:** for, while, do-while → repeat tasks.
    
- **Break & Continue:** skip or stop loops early.
    

### 🔹 String Handling

- Strings are **immutable objects** in Java.
    
- Common methods: `.length()`, `.substring()`, `.equals()`, `.toUpperCase()`.
    
- Also includes `StringBuilder` & `StringBuffer` for **mutable strings**.
    

### 🔹 Arrays

- Collection of elements of the same type.
    

`int[] arr = {1,2,3,4}; System.out.println(arr[0]);  // 1`

- Supports 1D, 2D, and jagged arrays.
    

### 🔹 Date and Time

- Old: `Date`, `Calendar`.
    
- New (Java 8+): `LocalDate`, `LocalTime`, `LocalDateTime`, `DateTimeFormatter`.
    

### 🔹 Searching & Sorting

- Searching: Linear search, Binary search.
    
- Sorting: Bubble sort, Selection sort, Quick sort, Merge sort.
    
- Built-in: `Arrays.sort(arr)`.
    

### 🔹 Object Oriented Programming

- **Class & Object** → Blueprint and instance.
    
- **Inheritance** → One class inherits another.
    
- **Polymorphism** → Method overloading & overriding.
    
- **Abstraction** → Abstract classes, interfaces.
    
- **Encapsulation** → Data hiding using private fields + getters/setters.
    

### 🔹 Collections Framework

- Ready-made data structures like `ArrayList`, `LinkedList`, `HashSet`, `HashMap`.
    
- Provide dynamic storage and efficient searching.
    

### 🔹 Functional Programming (Java 8+)

- **Lambda Expressions** → `(a,b) -> a+b`.
    
- **Functional Interfaces** → Single abstract method (e.g., Runnable, Comparator).
    
- **Method References** → `System.out::println`.
    
- **Optional Class** → Handle null values safely.
    
- **Streams & Parallel Streams** → Process collections in a functional style.
    

### 🔹 Exception Handling

- Deal with runtime errors using `try, catch, finally, throw, throws`.
    

`try {   int a = 10/0; } catch(ArithmeticException e) {   System.out.println("Error: " + e); }`
