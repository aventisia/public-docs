# **Update Data Table Item**

## **Description**

This configuration enables updating a specific item in a data table by modifying a column value for a selected row.

---
![alt text](../../assests/workflow-logics/assests%20datatable/update-data-table-item.png)

## **Configuration Details**

### **Data Table:** `DT_StudentData`

- The target table where the update will be performed.

### **Column:** `"EmpName"`

- The specific column that will be updated.

### **Row:** `1`

- The row index where the update will be applied.

### **New Value:** `"Gemmini"`

- The new value that will replace the existing one in the specified row and column.

---

## **Example Use Case**

### **Input Data**

#### **Existing Data Table (`DT_StudentData`):**

| Index | EmpID | EmpName  | Age | Department |
|-------|-------|---------|-----|------------|
| 1     | 101   | Alice   | 25  | HR         |
| 2     | 102   | Bob     | 28  | Finance    |
| 3     | 103   | Charlie | 30  | IT         |

---

### **Action Performed**

- **The `EmpName` field for row `1` is updated from `"Alice"` to `"Gemmini"`**

---

### **Output After Update**

#### **Updated `DT_StudentData` Table:**

| Index | EmpID | EmpName  | Age | Department |
|-------|-------|---------|-----|------------|
| 1     | 101   | Gemmini | 25  | HR         |
| 2     | 102   | Bob     | 28  | Finance    |
| 3     | 103   | Charlie | 30  | IT         |

---

## **Summary**

- **Action Performed:** The `EmpName` of the first row was modified.
- **Result:** `"Alice"` was replaced with `"Gemmini"` in row `1`.
- **Use Case:** This feature is useful for scenarios such as updating employee details, correcting errors, or modifying records dynamically.
