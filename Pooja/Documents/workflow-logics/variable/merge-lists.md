# Merge Lists  

## Description

The **Merge Lists** feature combines two lists into a single list without modifying the original lists.  

---  
![alt text](../../assests/workflow-logics/assests%20variable/merge-lists.png)

## Configuration Options  

- **First List** (Required)  
  - Specifies the first list to be merged.  

- **Second List** (Required)  
  - Specifies the second list to be merged.  

- **Output**  
  - **OutputList**: The resulting merged list. The initial lists remain unchanged.  

---  

## Input & Output Example  

| **First List (var_List1)** | **Second List (var_List2)** | **Output List** |
|----------------------------|----------------------------|-----------------|
| `[1, 2, 3]`                | `[4, 5, 6]`                | `[1, 2, 3, 4, 5, 6]` |
| `['A', 'B']`               | `['C', 'D']`               | `['A', 'B', 'C', 'D']` |
| `[10, 20]`                 | `[30, 40, 50]`             | `[10, 20, 30, 40, 50]` |

---  

## Summary

This feature is useful for **combining multiple lists** while keeping the original lists intact.
