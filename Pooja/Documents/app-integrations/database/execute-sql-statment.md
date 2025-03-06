# Execute SQL Statement

## **Description**

This screenshot demonstrates an interface for executing an SQL statement. Users can establish a database connection using a connection string and execute SQL queries.

![alt text](execute-sql-statment-1.png)

---

## **Input Fields**

### **1. Get Connection By**

- A dropdown field to select the method of establishing the SQL connection.
- In this case, the selected option is **"Connection string"**.

### **2. Connection String**

- A text input field containing the SQL connection string.
- Example format:

  ```plaintext

  Server=myServerAddress;Database=myDataBase;User Id=myUsername;Password=myPassword;

- This string includes necessary credentials to access the database.

### **3. SQL Connection**

An input field where users can specify an existing SQL connection handle.
This field is currently empty, indicating that a new connection might be required.
Additional Options

### **4. Advanced**

A collapsible section labeled "Advanced".
Likely contains additional settings related to SQL execution.

### **Summary**

This tool is designed to execute SQL queries by either:

Establishing a new connection using a connection string.
Utilizing an existing SQL connection.
It includes advanced options for additional configurations and error-handling mechanisms to manage execution failures efficiently.
