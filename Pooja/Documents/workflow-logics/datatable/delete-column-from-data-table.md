# **Delete Column from Data Table**

## **Description**  

This configuration allows deleting a specified column from a given data table.

---

![alt text](../../assests/workflow-logics/assests%20datatable/delete-column-from-data-table.png)

## **Configuration Details**

### **Data Table:** `DT_StudentData`

- The table from which the column will be removed.

### **Specify Column With:** `Name`

- The column reference method used to identify the column.

### **Column Name:** `Score`

- The column **"Score"** will be deleted.

---

## **Example Use Case**

### **Input Data Table (`DT_StudentData`)**

| Index | StudentID | Name     | Score |
|-------|----------|---------|------|
| 1     | S001     | Alice    | 85   |
| 2     | S002     | Bob      | 78   |
| 3     | S003     | Charlie  | 92   |

---

### **Action Performed**

- The column `"Score"` is **removed** from the table.

---

### **Output After Column Deletion**

| Index | StudentID | Name     |
|-------|----------|---------|
| 1     | S001     | Alice    |
| 2     | S002     | Bob      |
| 3     | S003     | Charlie  |

---

## **Summary**

- **Before:** Table had columns `"StudentID"`, `"Name"`, and `"Score"`.
- **After:** `"Score"` column was removed.
- **Use Case:** Useful for cleaning up unnecessary data, removing sensitive information, or optimizing storage.
