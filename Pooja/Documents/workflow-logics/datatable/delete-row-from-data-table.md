# **Delete Row from Data Table**

## **Description**

This configuration allows users to delete a specific row from a given data table.

---
![alt text](../../assests/workflow-logics/assests%20datatable/delete-row-from-data-table.png)

## **Configuration Details**

### **Data Table:** `DT_StudentData`

- This is the table from which a row will be deleted.

### **Row Index:** `3`

- Specifies the row position to be removed.
- Indexing typically starts from `1`, meaning the third row will be deleted.

---

## **Example Use Case**

### **Input Data**

#### **Existing Data Table (`DT_StudentData`):**

| Index | Student_ID | Name    | Age | Grade |
|-------|------------|--------|-----|-------|
| 1     | 101        | Alice  | 20  | A     |
| 2     | 102        | Bob    | 22  | B     |
| 3     | 103        | Charlie | 21  | A-    |
| 4     | 104        | David  | 23  | B+    |

---

### **Action Performed**

- **Row at index `3` (Charlie’s record) is deleted.**

---

### **Output After Deletion**

#### **Updated `DT_StudentData` Table:**

| Index | Student_ID | Name    | Age | Grade |
|-------|------------|--------|-----|-------|
| 1     | 101        | Alice  | 20  | A     |
| 2     | 102        | Bob    | 22  | B     |
| 3     | 104        | David  | 23  | B+    |

---

## **Summary**

- **Action Performed:** The third row (Charlie’s record) was removed.
- **Result:** The table now has one less record.
- **Use Case:** Useful for scenarios like student withdrawal, employee removal, or inventory management where data updates dynamically.
