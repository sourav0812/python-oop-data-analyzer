# Student Project Data Analyzer – OOP in Python

## Overview
An object-oriented Python program that models student research 
projects and performs statistical analysis on project data. 
Built using class inheritance, encapsulation, and exception handling.

## Skills & Tools
- Python, Object-Oriented Programming (OOP)
- Class design, inheritance, encapsulation (private attributes)
- Statistics from scratch: mean, median, sample variance
- Exception handling (TypeError, ZeroDivisionError)
- Unit testing

## What This Project Does
1. Defines a `Student` base class with student ID, major, 
   and university attributes
2. Defines a `Project` subclass that inherits from `Student` 
   and adds project-specific data and behavior
3. Performs statistical analysis (mean, median, sample variance) 
   on project data points — calculated manually without built-in methods
4. Handles edge cases: empty data lists, non-numerical inputs
5. Includes 8 test cases covering normal use and error conditions

## Key Concepts Demonstrated
- Inheritance (`Project` extends `Student`)
- Private attributes (`__analysis_results`, `__active`)
- Getter/setter methods (`get_results`, `is_active`, `set_active`)
- Exception handling with `try/except` and `raise`
