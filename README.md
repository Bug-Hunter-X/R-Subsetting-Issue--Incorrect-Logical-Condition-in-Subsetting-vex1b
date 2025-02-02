# R Subsetting Issue: Incorrect Logical Condition

This repository demonstrates a common error encountered when subsetting data frames in R based on logical conditions. The error arises from an incorrect application of logical operators, leading to unexpected results. The provided code showcases the incorrect and correct ways to subset a data frame, explaining the problem and providing the correct solution.  The solution includes examples using both the `[` operator and the `subset` function for improved clarity.

## Problem Description

The issue lies in how logical conditions are specified within the subsetting operation.  An incorrect understanding of logical operators (AND, OR) can result in unintended row selections.  The example highlights the difference between using `|` (OR) and `&` (AND), demonstrating the importance of precise logical condition definition.