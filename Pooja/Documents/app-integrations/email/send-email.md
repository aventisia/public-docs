# **Send Email**

## **Description**

This interface allows users to **send an email** by specifying the sender, recipient(s), subject, and body content. This interface allows users to configure **SMTP settings** for sending emails, including defining the SMTP server, port, authentication, and SSL settings.

![alt text](../../assests/app-integrations/assests%20email/send-email.png)

![alt text](../../assests/app-integrations/assests%20email/send-email2.png)

---

## **Input Fields**

### **1. From**

- Specifies the sender's email address.
- **Value:** `user@example.com`

### **2. Sender Display Name**

- Specifies the sender’s display name.
- **Value:** `XYZ`

### **3. To**

- Specifies the primary recipient's email address.
- **Value:** `user@example.com`

### **4. CC (Carbon Copy)**

- Specifies additional recipients who will receive a copy of the email.
- **Value:** _(Empty)_

### **5. BCC (Blind Carbon Copy)**

- Specifies additional recipients who will receive a hidden copy of the email.
- **Value:** _(Empty)_

### **6. Subject**

- Specifies the subject line of the email.
- **Value:** `Project Deadline`

### **7. Body**

- Contains the main content of the email.

- **Value:**

### **1. Body is HTML**

- Specifies whether the email body should be interpreted as HTML.
- **Value:** Disabled (☐)

### **2. Attachments**

- Allows the user to attach files to the email.
- **Value:** _(Empty)_

---

## **SMTP Server Configuration**

### **3. SMTP Server**

- Specifies the SMTP server to be used for sending emails.
- **Value:** `smtp.gmail.com`

### **4. Server Port**

- Defines the port number for the SMTP server.
- **Value:** `25` (Default SMTP port)

### **5. Enable SSL**

- Determines whether to use a **secure connection** (SSL) for email transmission.
- **Value:** Disabled (☐)

### **6. SMTP Server Needs Authentication**

- Specifies whether the SMTP server requires authentication.
- **Value:** Disabled (☐)

---

## **Summary**

This tool enables users to configure **SMTP settings** for sending emails, including:

- **SMTP server & port selection**
- **SSL encryption settings**
- **Authentication requirements**
- **Support for HTML email bodies and attachments**
