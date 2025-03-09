# **Insert Row into Data Table**

## **Descriptoin**

This dialog allows users to insert a new row into an existing data table within an automated workflow.

---

![alt text](../../assests/workflow-logics/assests%20datatable/inser-row-into-data-table.png)

## Configuration Details

### **Data Table:** `DT_StudentData`

- This is the target table where new data will be added.
- It likely stores student-related information.

### **Insertion Location:**  

- **Option Selected:** `"End of data table"`
- This means the new row will be appended at the bottom of the table.

### **New Value(s):**  

- **Variable Used:** `DT_newRow`
- This holds the new data that will be inserted into the table.

---

## Example Use Case

### Input Data

#### **Existing Data Table (`DT_StudentData`):**

| Student_ID | Name      | Age | Grade |
|------------|----------|-----|-------|
| 101        | Alice    | 20  | A     |
| 102        | Bob      | 22  | B     |

#### **New Row (`DT_newRow`):**

| Student_ID | Name  | Age | Grade |
|------------|------|-----|-------|
| 103        | Charlie | 21  | A-    |

---

### Output After Insertion

#### **Updated `DT_StudentData` Table:**

| Student_ID | Name    | Age | Grade |
|------------|--------|-----|-------|
| 101        | Alice  | 20  | A     |
| 102        | Bob    | 22  | B     |
| 103        | Charlie | 21  | A-    |

---

## Summary

- **Action Performed:** A new student record (`DT_newRow`) was added to the **end** of `DT_StudentData`.  
- **Result:** The table now contains an additional row with the new student’s details.
- **Use Case:** Useful in scenarios where data is continuously updated, such as student registrations, employee records, or inventory management.
