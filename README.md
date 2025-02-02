# PHP Null Value Strict Comparison Unexpected Behavior

This repository demonstrates an uncommon bug in PHP related to strict comparisons (===) and null values. The issue arises when the function receives null values as input. In certain contexts, the behavior might not align with expectations, leading to unforeseen consequences.

The `bug.php` file showcases the erroneous code, and `bugSolution.php` presents the corrected version with a more robust approach for handling null values.

## Setup

1. Clone the repository.
2. Run the scripts using a PHP interpreter.

## Problem

The strict comparison `===` doesn't always correctly evaluate null values, especially when mixed with other comparison types.