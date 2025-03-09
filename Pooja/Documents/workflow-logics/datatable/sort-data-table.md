# Sort Data Table  

## **Description**

This operation sorts the data in the **DT_StudentData** table based on the **StudName** column in **ascending/descending order**.  

![alt text](../../assests/workflow-logics/assests%20datatable/sort-data-table.png)

## **Input**

| Parameter          | Value             | Description                                |
|-------------------|-----------------|--------------------------------------------|
| **Data Table**    | `DT_StudentData` | The table to be sorted.                    |
| **Specify Column With** | `Name`  | The column type to specify sorting.        |
| **Column Name**   | `StudName`       | The specific column used for sorting.      |
| **Order**         | `Ascending`      | The sorting order (Ascending/Descending). |

## **Output**

| Parameter        | Description                            |
|-----------------|----------------------------------------|
| **Sorted Table** | The table is now sorted by `StudName`. |

---

## **Summmary**

- **Sorts** all rows based on **StudName**.  
- **Ascending order** (A → Z, 1 → 100).  
- **Preserves all data** while rearranging rows.  
