# **Trim Text**

## **Description**

The **Trim Text** operation removes **unwanted characters** (such as whitespace, special characters, or custom-defined characters) from the **beginning and/or end** of a given text string. This is particularly useful for **cleaning user input, standardizing data, and ensuring consistency** in text-based applications.

This operation supports **multiple trimming options**:

- **Whitespace trimming**: Removes spaces, tabs, and newlines from the start and end of the text.
- **Custom character trimming**: Removes specific characters, such as punctuation or special symbols.
- **Advanced trimming**: Allows removing characters from either **only the start, only the end, or both sides** of the text.

---

 ![alt text](../../assests/data-transformation/assests%20text-action/trim-text.png)

## **Input Parameters**

| Parameter         | Value                                            | Description |
|------------------|------------------------------------------------|-------------|
| **Text to Trim** | `Robotics Process Automation`                   | The original text that needs to be cleaned. |
| **What to Trim** | `Whitespace characters from the beginning and end` | Defines the type of trimming to be applied. |

---

## **Output**

| Parameter      | Description |
|---------------|-------------|
| **TrimmedText** | The new text with the unwanted characters removed. |

## **Example Use Cases**

### **Example 1: Trimming Whitespace**

#### **Scenario**

A user submits a form with the input `"  Robotics Process Automation  "` (including leading and trailing spaces). The spaces need to be removed before processing.

#### **Configuration**

- **Text to Trim:**`"  Robotics Process Automation  "`
- **What to Trim:**`Whitespace characters from the beginning and end`

#### **Result :** Robotics Process Automation

---

## **Summary**

- **Removes extra spaces** from user input fields.
- **Cleans up text** for better **data processing and consistency**.
- Helps **avoid errors in comparisons** when checking for text equality.
- Ensures **uniform formatting** in structured data, logs, or reports.
