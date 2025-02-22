# Inconsistent Width Calculation in CSS `calc()`

This repository demonstrates a subtle yet impactful error in CSS that involves using a unitless value within a `calc()` function for the `width` property. This error leads to inconsistencies in how the width is rendered across different browsers.

## The Problem

The issue arises when you provide a numerical value without specifying its unit (e.g., `px`, `em`, `rem`, `%`) within a `calc()` function used for the `width`.  Browsers interpret this differently, resulting in inconsistent rendering and unexpected behavior.

## Reproduction

The `bug.css` file contains the erroneous CSS code. Observe the varying widths of the element when rendered in different browsers.

## Solution

The `bugSolution.css` file shows how to correct this issue by explicitly specifying a unit for all values within the `calc()` function.