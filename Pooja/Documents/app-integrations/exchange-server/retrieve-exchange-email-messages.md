# **Retrieve Exchange Email Messages**

## **Description**

This interface enables users to **retrieve email messages** from an Exchange server, allowing configuration of mailbox type, folders, filters, and read status.

![alt text](../../assests/app-integrations/assests%20exchange-server/retrieve-exchange-email-messages1.png)

![alt text](../../assests/app-integrations/assests%20exchange-server/retrieve-exchange-email-messages2.png)

---

## **Input Fields**

### **1. Exchange Connection**

- Specifies the **Exchange connection** to be used for retrieving emails.
- **Value:** _(User must select an existing connection)_

### **2. Mailbox Type**

- Defines the type of mailbox from which emails will be retrieved.
- **Value:** `Personal`

### **3. Retrieve Email Messages from Custom Folder**

- Enables retrieval of emails from a **custom folder** instead of a predefined Exchange folder.
- **Status:** Disabled (Retrieving from a standard Exchange folder)

### **4. Exchange Folder** (Required)

- Specifies the Exchange folder from which emails will be retrieved.
- **Value:**

```plaintext
Inbox
Deleted items
Drafts
Outbox
Sent items
Junk email
```

### **5. Retrieve**

- Filters emails based on read/unread status.
- **Value:**

```plaintext
All email messages
Unread email messages only
Read email messages only
```

### **6. Mark as Read**

- Defines whether retrieved emails should be **marked as read** after retrieval.
- **Status:** Enabled (Emails will be marked as read)

### **7. From Contains**

- Filters emails based on the **sender's email address**.
- **Example:** `example@domain.com`

### **8. To Contains**

- Filters emails based on the **recipient's email address**.
- **Example:** `recipient@domain.com`

### **9. Subject Contains**

- Retrieves emails where the **subject line** contains specific keywords.
- **Example:** `Project Deadline`

### **10. Body Contains**

- Searches emails for specified keywords in the **email body**.
- **Example:** `Meeting Agenda`

### **11. Attachments**

- Defines how attachments should be handled.
- **Options:**
  - `Ignore attachments`
  - `Save attachments` (Selected)
  - `Process attachments`

---

## **Output**

- **RetrievedEmails** (Enabled)
  - Stores retrieved emails for **further processing** as Exchange mail objects.

---

## **Summary**

This tool allows users to:

- **Retrieve emails** from an Exchange mailbox.
- **Choose a specific folder** (e.g., Inbox).
- **Filter unread emails only** for retrieval.
- **Mark emails as read** after retrieval.
- Apply **filters** based on sender, recipient, subject, and content.
- Handle **email attachments**.
- Store retrieved emails for **later processing**.
