# Open FTP Connection

## Description

The **Open FTP Connection** operation establishes a connection to an FTP server using a set of required credentials and configurations.

![alt text](../../assests/app-integrations/assests%20ftp/open-ftp-connection.png)

---

## **Input Parameters**

| Parameter     | Description                                             | Example Value                |
|--------------|---------------------------------------------------------|------------------------------|
| **Host**     | The **FTP server address** (IP or domain).              | `ftp.example.com`            |
| **Port**     | The port number for the **FTP server**. Default: `21`.  | `21`                         |
| **Active Mode** | Enables Active Mode instead of Passive Mode.         | `Enabled` / `Disabled`       |
| **Password** | The **password** for authentication.                    | `MySecurePassword`           |
| **Timeout**  | The time (in seconds) before the connection times out.  | `10`                         |

---

## **Process Flow**

1. The user enters **FTP server details** such as Host, Port, and Password.
2. The system attempts to **establish a connection** using the provided details.
3. If successful, a **connection handle** is created.
4. If an error occurs (e.g., incorrect credentials, server down), the **On Error** section handles it.

---

## **Output Parameters**

| Parameter        | Description                                             |
|-----------------|---------------------------------------------------------|
| **FTP Connection** | A reference handle for the **FTP session**.           |
| **Error Message**  | If the connection fails, an error message is returned.|

---

## **Example Use Cases**

### **1. Connecting to an FTP Server (Successful Case)**

#### **Input:**

Host: ftp.example.com Port: 21 Active Mode: Disabled Password: MySecurePassword Timeout: 10

#### **Expected Output:**

- FTP **Connection handle** is created successfully.
- User can now **upload/download** files from the FTP server.

---

## **Summary**

- The **Open FTP Connection** operation allows connecting to an FTP server using a **hostname, port, and password**.
- A successful connection returns an **FTP Connection handle**.
- This handle is used for **file transfers** (upload/download).
- Proper **error handling** ensures a robust FTP connection process.

---

✅ **Use this operation to efficiently manage FTP transfers!**

