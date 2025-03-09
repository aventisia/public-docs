# Truncate Number  

## Description

The **Truncate Number** feature allows users to modify a numerical value by extracting specific parts or applying rounding rules.  

![alt text](../../assests/workflow-logics/assests%20variable/truncate-number.png)

## Configuration Options  

- **Number to Truncate** (Required)  
  - Specifies the numerical value to be truncated.  

- **Operation** (Required)  
  - Defines the truncation method to be applied. Options include:  
    - **Get integer part**: Extracts only the whole number portion by removing the decimal part.  
    - **Get decimal part**: Retrieves only the fractional portion of the number, discarding the integer part.  
    - **Round number**: Rounds the number to the nearest whole number based on standard rounding rules.  

---  

## Input & Output Examples  

| **Number to Truncate** | **Operation**        | **Output (Truncated Value)** |
|------------------------|----------------------|------------------------------|
| `23.6789`             | Get integer part     | `23`                         |
| `-45.987`             | Get integer part     | `-45`                        |
| `100.45`              | Get integer part     | `100`                        |
| `0.99`                | Get integer part     | `0`                          |
| `23.6789`             | Get decimal part     | `0.6789`                      |
| `-45.987`             | Get decimal part     | `-0.987`                      |
| `100.45`              | Get decimal part     | `0.45`                        |
| `0.99`                | Get decimal part     | `0.99`                        |
| `23.6789`             | Round number        | `24`                         |
| `-45.987`             | Round number        | `-46`                        |
| `100.45`              | Round number        | `100`                        |
| `0.99`                | Round number        | `1`                          |

---  

## Summary

This feature is particularly useful for **data transformation**, **decimal handling**, and **ensuring numerical precision** in calculations.  
