# CPP06

## Project Overview

This project explores different types of C++ casts and type conversions. It consists of three exercises that demonstrate scalar type conversion, serialization, and type identification using dynamic casting.

The project focuses on:
- **C++ Casts**: Understanding and implementing different casting mechanisms
- **Type Conversion**: Converting between scalar types (char, int, float, double)
- **Serialization**: Converting pointers to integers and back
- **Runtime Type Identification**: Using dynamic_cast to identify object types

---

### Exercise 00: Conversion of Scalar Types

A `ScalarConverter` class that converts string representations to different scalar types.

**Features:**
- Converts input to char, int, float, and double
- Handles special cases (nan, inf, -inf)
- Detects impossible conversions
- Uses static methods (non-instantiable class)

---

### Exercise 01: Serialization

A `Serializer` class that demonstrates pointer serialization/deserialization.

**Features:**
- Converts pointer to `uintptr_t` (serialize)
- Converts `uintptr_t` back to pointer (deserialize)
- Uses reinterpret_cast for type conversion
- Non-instantiable class with static methods

---

### Exercise 02: Identify Real Type

Type identification system using polymorphism and dynamic_cast.

**Features:**
- Base class with virtual destructor
- Three derived classes (A, B, C)
- Random object generation
- Type identification by pointer and reference
- Uses dynamic_cast for safe downcasting

---

## Key Concepts Demonstrated

### 1. Static Cast vs Dynamic Cast
- **Static Cast**: Compile-time type conversion
- **Dynamic Cast**: Runtime type checking with polymorphic classes

### 2. Reinterpret Cast
- Low-level casting between unrelated types
- Used for pointer-to-integer conversions

### 3. Type Safety
- Proper error handling for invalid conversions
- Safe downcasting with dynamic_cast

### 4. Non-instantiable Classes
- Pure virtual destructors
- Static-only interfaces

---

## Learning Objectives

- Understand different C++ casting operators
- Learn about type conversion and safety
- Practice with static class design
- Explore runtime type identification
- Handle edge cases in type conversions
