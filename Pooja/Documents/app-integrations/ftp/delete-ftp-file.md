# **Delete FTP File**

## Description

The **Delete FTP File** operation allows users to remove a specified file from an FTP server.

![alt text](../../assests/app-integrations/assests%20ftp/delete-ftp-file.png)

---

## **Input Parameters**

| Parameter         | Description                                   | Example Value           |
|------------------|---------------------------------------------|-------------------------|
| **FTP Connection** | The handle for an active FTP session.     | `FTP_Connection_1`      |
| **Files to delete** | The full path to the file to be deleted. | `/public/uploads/file1.txt` |

---

## **Process Flow**

1. A **valid FTP connection** is selected.
2. The **file path** to be deleted is specified.
3. The system attempts to **delete the file** on the FTP server.
4. If successful, a **confirmation message** is returned.
5. If the operation fails (e.g., file not found, permission denied), an **error message** is returned.

---

## **Expected Output**

| Parameter      | Description                                       |
|---------------|---------------------------------------------------|
| **Success Message** | Confirms that the file has been deleted.     |
| **Error Message**   | If deletion fails, an error message is shown. |

---

## **Example Use Cases**

### ✅ **1. Successfully Deleting a File**

#### **Input:**

FTP Connection: FTP_Connection_1 Files to delete: /public/uploads/file1.txt

#### **Expected Output:**

Success: File '/public/uploads/file1.txt' has been deleted.

---

## **Summary**

- The **Delete FTP File** operation removes a **specified file** from an FTP server.
- Requires a **valid FTP connection** and a **target file path**.
- If successful, the file is **permanently deleted**.
- If failed, an **error message is returned**.
- Important for **managing FTP storage and cleanup**.

---

✅ **Use this operation to efficiently manage and delete files on your FTP server!** 🚀