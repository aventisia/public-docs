# Sort List  

## Description

The **Sort List** feature enables users to arrange the elements of a list in a specified order, either in ascending or descending sequence.  

---  
![alt text](../../assests/workflow-logics/assests%20variable/sort-list.png)

## Configuration Options  

- **List to Sort** (Required)  
  - Specifies the list that needs to be sorted.  

- **Sort by List Item's Properties** (Optional)  
  - If the list contains objects (such as files, folders, etc.), enabling this option allows sorting by a specific property.  
  - If disabled, the elements will be sorted by their default property (e.g., file objects will be sorted by their full path).  

- **First Property to Sort By** (Required if sorting by properties)  
  - Defines the primary property to use for sorting when the list contains objects.  

- **Sort Order** (Required)  
  - Determines whether the list should be sorted in **Ascending** or **Descending** order.  

---  

## Input & Output Example  

| **Input List**                     | **Sort Order** | **Output List**                |
|--------------------------------------|---------------|--------------------------------|
| `[4, 2, 9, 1]`                      | Ascending     | `[1, 2, 4, 9]`                 |
| `['Banana', 'Apple', 'Cherry']`     | Ascending     | `['Apple', 'Banana', 'Cherry']`|
| `['Banana', 'Apple', 'Cherry']`     | Descending    | `['Cherry', 'Banana', 'Apple']`|
| `[{'name': 'FileB'}, {'name': 'FileA'}]` | Ascending | `[{'name': 'FileA'}, {'name': 'FileB'}]` |

---  

## Summary

This feature is useful for **organizing data**, **sorting numerical values**, and **arranging structured lists** efficiently.  
