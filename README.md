# 📘 Learn Core Java

 >⚠️**Please read before reviewing this repository**

I am a **Computer Science graduate** with **strong fundamentals in C/C++ and Object-Oriented Programming (OOP)**.  
In my professional role, my organization advised me to transition into **backend development using Spring Boot** as part of a long-term goal to become an **ERP specialist**.

### 🔹 My Learning Strategy
- I do not memorize Java syntax mechanically
- I scan Java concepts quickly
- I practice and document only Java-specific or hard-to-retain topics
- I focus on:
  - Differences between **Java vs C/C++**
  - Concepts required for **Spring Boot & enterprise development**
  - Core APIs used in **real-world backend systems**

This repository acts as a personal **revision notebook**

## 🛠️ Environment Setup (To Run Java Locally)

You need the following:

- **JDK (Java Development Kit)**
- **IDE (any one)**
  - IntelliJ IDEA  
  - Eclipse  
  - VS Code
- **Environment Variables**
  - `JAVA_HOME`
  - Add JDK `bin` directory to `PATH`
- **Run a Java File Using Terminal**
```bash
javac Filename.java
java Filename
```
# 📝 Java Important Key Notes
1. Class names should start with an **uppercase letter**
2. Java is **case-sensitive**
   - `MyClass` ≠ `myclass`
3. Single-line comments: `//`
4. Multi-line comments: `/* ... */`

## 🧾 Variable Naming Conventions

- Letters, digits, `_`, `$` allowed
- Must start with a **letter**
- Prefer **lowercase camelCase**
- No whitespace
- Case-sensitive
- Java **reserved keywords cannot be used**

## 📊 Data Types Overview

### Primitive Types
- `byte`, `short`, `int`, `long`
- `float`, `double`
- `boolean`
- `char`

### Non-Primitive Types
- `String` **•** `Arrays` **•** `Classes` & `Objects`

## 🔢 Float vs Double (Precision Matters)

| Type   | Precision |
|--------|-----------|
| float  | 6–7 digits |
| double | ~16 digits |

**Note:** Use `double` unless memory optimization is critical.

## 🔄 Type Casting in Java
- Widening Casting (automatic) - converting a smaller type to a larger type size
`byte` -> `short` -> `char` -> `int` -> `long` -> `float` -> `double`

- Narrowing Casting (manual) - converting a larger type to a smaller type size
`double` -> `float` -> `long` -> `int` -> `char` -> `short` -> `byte`

## ➗ Operator Precedence (High → Low)
1. Parentheses `()`
2. `* / %`
3. `+ -`
4. Relational `> < >= <=`
5. Equality `== !=`
6. Logical AND `&&`
7. Logical OR `||`
8. Assignment `=`

## 🔗 Numbers & Strings

- Number + Number → Numeric result
- String + String → Concatenation
- Number + String → Concatenation

## 🔤 Escape Characters

| Escape | Meaning |
|-------|--------|
| `\'` | Single quote |
| `\"` | Double quote |
| `\\` | Backslash |
| `\n` | New line |
| `\t` | Tab |
| `\b` | Backspace |
| `\r` | Carriage return |
| `\f` | Form feed |

## 🔢 Important Math Functions

- `Math.round(x)` → nearest integer
- `Math.ceil(x)` → round up
- `Math.floor(x)` → round down
- `Math.random()` → value between **0.0 (inclusive)** and **1.0 (exclusive)**

## Array & for-each Loop

```java
String[] cars = new String[4];
String[] persons = {"A", "B", "C"};
int len = persons.length; // use length property to get length of any array
```
## Parameters Vs Arguments
- **Parameters->** variable in method defination
- **Arguments->** actual values passed

## Class Vs Object
- Class -> Blueprint
- Object -> Instance of a class

## Comparator vs. Comparable
- A comparator is an object with one method that is used to compare two different objects.
- A comparable is an object which can compare itself with other objects.

# 📚 Covered Topics

**Java Basics**  
**•** Syntax **•** Variables **•** Data Types **•** Operators **•** Strings **•** Math **•** Conditions **•** Loops **•** Arrays

**Methods**  
**•** Parameters **•** Overloading **•** Scope **•** Recursion

**Object-Oriented Programming (OOP)**  
**•** Encapsulation **•** Inheritance **•** Polymorphism **•** Abstraction **•** Interfaces **•** Enums **•** Inner Classes **•** Anonymous Classes

**Exceptions & Debugging**  
**•** Try-Catch **•** Multiple Exceptions **•** Try-with-resources

**File Handling & I/O**  
**•** File Read **•** File Write **•** File Delete **•** Streams **•** BufferedReader **•** BufferedWriter

**Collections & Data Structures**  
**•** List **•** Set **•** Map **•** ArrayList **•** LinkedList **•** HashMap **•** TreeMap **•** Iterators **•** Algorithms

**Advanced Java**  
**•** Wrapper Classes **•** Generics **•** Annotations **•** Regex **•** Threads **•** Lambda Expressions
