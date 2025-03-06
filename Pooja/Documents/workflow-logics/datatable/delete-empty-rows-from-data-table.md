# **Delete Empty Rows from Data Table**

This configuration removes any empty rows from a specified data table.

---

![alt text](delete-empty-rows-from-data-table-1.png)

## **Configuration Details**

### **Data Table:** `DT_StudentData`

- The table from which empty rows will be deleted.

---

## **Example Use Case**

### **Input Data Table (`DT_StudentData`)**

| Index | StudentID | Name    | Score |
|-------|----------|---------|------|
| 1     | S001     | Alice   | 85   |
| 2     |          |         |      |
| 3     | S002     | Bob     | 78   |
| 4     |          |         |      |
| 5     | S003     | Charlie | 92   |

---

### **Action Performed**

- All **empty rows** (rows with no values in any column) are **removed**.

---

### **Output After Deletion**

| Index | StudentID | Name    | Score |
|-------|----------|---------|------|
| 1     | S001     | Alice   | 85   |
| 2     | S002     | Bob     | 78   |
| 3     | S003     | Charlie | 92   |

---

## **Summary**

- **Before:** Table contained empty rows at index `2` and `4`.
- **After:** These rows were deleted.
- **Use Case:** Helps in cleaning up unnecessary empty data entries, making the dataset more structured and efficient.
