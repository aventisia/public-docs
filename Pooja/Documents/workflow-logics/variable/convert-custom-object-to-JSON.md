# Convert Custom Object to JSON

## Description

In software applications, data is often structured as **custom objects**, which are user-defined entities consisting of multiple attributes. Converting these objects into **JSON (JavaScript Object Notation)** makes data storage, transfer, and interoperability easier between different systems and programming languages.

![alt text](../../assests/workflow-logics/assests%20variable/convert-custom-object-to-JSON.png)

---

## **Input:**

To convert a custom object into JSON, the user needs to **provide or select** an object.

- **Custom Object:** The object must be structured with named attributes and values.
- **Supported Data Types:**

  - Strings (`"Alice Johnson"`)
  - Numbers (`101`)
  - Lists (`["Communication", "Recruitment", "Payroll"]`)
  - Nested objects (other objects within an object)

If the object is improperly structured or contains **unsupported types** (e.g., functions or complex objects), the conversion may fail.

---

## **Output:**

Once processed, the tool **serializes** the custom object into JSON format, preserving its structure.

- **Output Variable:** `customObjectAsJson`
- **Output Type:** String (JSON formatted)
- **Usage:** This JSON data can be used for:
  - **API communication**
  - **Database storage**
  - **Configuration files**
  - **Data exchange between applications**

### **Example JSON Output**

```json
{
    "emp_id": 101,
    "name": "Alice Johnson",
    "department": "HR",
    "skills": [
        "Communication",
        "Recruitment",
        "Payroll"
    ]
}
```

- The custom object is now converted into a **readable and structured JSON format**.
- The structure remains the same, ensuring data **integrity**.

---

## **Summary**

Custom objects are widely used in programming to structure data. Converting them to **JSON** enhances **data portability, interoperability, and efficiency**. This conversion ensures that structured data can be used across different applications seamlessly.
