# CPP-MODULES

This repository contains C++ learning modules covering fundamental to advanced concepts in C++ programming. Each module focuses on specific aspects of C++ and follows the C++98 standard.

## Module Overview

### 📁 CPP00 - Introduction to C++
**Topics Covered:**
- Namespaces
- Classes and basic member functions  
- stdio streams
- Initialization lists
- Static and const

**Compilation:** `cd CPP00 && make`

### 📁 CPP01 - Memory Management
**Topics Covered:**
- Memory allocation
- Pointers to members
- References
- Switch statement

**Compilation:** `cd CPP01 && make`

### 📁 CPP02 - Ad-hoc Polymorphism
**Topics Covered:**
- Ad-hoc polymorphism
- Operator overloading
- Orthodox Canonical class form

**Compilation:** `cd CPP02 && make`

### 📁 CPP03 - Inheritance
**Topics Covered:**
- Inheritance
- Diamond trap

**Compilation:** `cd CPP03 && make`

### 📁 CPP04 - Subtype Polymorphism
**Topics Covered:**
- Subtype polymorphism
- Abstract classes
- Interfaces

**Compilation:** `cd CPP04 && make`

### 📁 CPP05 - Exceptions
**Topics Covered:**
- Repetition and exceptions
- Try/catch blocks

**Compilation:** `cd CPP05 && make`

### 📁 CPP06 - C++ Casts
**Topics Covered:**
- C++ casts
- static_cast, dynamic_cast, const_cast, reinterpret_cast

**Compilation:** `cd CPP06 && make`

### 📁 CPP07 - Templates
**Topics Covered:**
- C++ templates
- Function templates and class templates

**Compilation:** `cd CPP07 && make`

### 📁 CPP08 - Templated Containers
**Topics Covered:**
- Templated containers
- Iterators and algorithms

**Compilation:** `cd CPP08 && make`

### 📁 CPP09 - STL
**Topics Covered:**
- STL containers and algorithms
- Advanced container usage

**Compilation:** `cd CPP09 && make`

## Getting Started

1. Clone the repository
2. Navigate to any module directory (CPP00 to CPP09)
3. Run `make` to compile the module
4. Execute the compiled program to see the module introduction

## Compilation Requirements

- C++ compiler with C++98 standard support
- Make utility
- All modules compile with flags: `-Wall -Wextra -Werror -std=c++98`

## Project Structure

```
CPP-MODULES/
├── CPP00/          # Introduction to C++
├── CPP01/          # Memory Management  
├── CPP02/          # Ad-hoc Polymorphism
├── CPP03/          # Inheritance
├── CPP04/          # Subtype Polymorphism
├── CPP05/          # Exceptions
├── CPP06/          # C++ Casts
├── CPP07/          # Templates
├── CPP08/          # Templated Containers
├── CPP09/          # STL
└── README.md       # This file
```

Each module contains:
- `main.cpp` - Main source file with module introduction
- `Makefile` - Build configuration