# CSS Calc() Nesting Issue

This repository demonstrates an uncommon issue related to nesting the `calc()` function in CSS when combining percentage and pixel units.  Some browsers may handle nested `calc()` functions inconsistently, especially when mixing units.  This can lead to unexpected layout issues.

## Problem
The problem lies in nesting `calc()` functions with mixed units (percentages and pixels) within the inner `calc()` function.  This can cause inconsistencies across browsers and lead to unexpected rendering results.

## Solution
The solution involves simplifying the nested `calc()` function or using alternative approaches, such as pre-calculating the values or using CSS variables, to ensure consistent and predictable behavior across browsers.

## Files
- `bug.css`: Demonstrates the CSS code causing the issue.
- `bugSolution.css`: Shows a revised approach to fix the problem.