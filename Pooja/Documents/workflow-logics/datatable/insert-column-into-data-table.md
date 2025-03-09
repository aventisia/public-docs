# **Insert Column into Data Table**

## **Description**

This configuration allows inserting a new column into the specified data table.

---

![alt text](../../assests/workflow-logics/assests%20datatable/insert-column-into-data-table.png)

## **Configuration Details**

### **Data Table:** `DT_StudentData`

- The table where the new column will be added.

### **Into Location:** `End of data table`

- The new column will be inserted at the last position of the table.

### **Column Name:** `StudRemark`

- The newly inserted column will be named `"StudRemark"`.

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

- Insert a new column named **"StudRemark"** at the **end** of the data table.

---

### **Output After Column Addition**

| Index | StudentID | Name     | Score | StudRemark |
|-------|----------|---------|------|------------|
| 1     | S001     | Alice    | 85   |            |
| 2     | S002     | Bob      | 78   |            |
| 3     | S003     | Charlie  | 92   |            |

---

## **Summary**

- **Before:** Table had columns `"StudentID"`, `"Name"`, and `"Score"`.
- **After:** `"StudRemark"` column was added at the **end**.
- **Use Case:** This can be useful for adding remarks, status updates, or additional student-related data.
