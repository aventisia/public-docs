# **Parse Text Operation**

## **Description**

The **Parse Text** operation searches for a specified substring within a given text and extracts its occurrence(s).

---
![alt text](../../assests/data-transformation/assests%20text-action/parse-text.png)

## **Configuration Options**

| Parameter                  | Value               | Description |
|----------------------------|---------------------|-------------|
| **Text to parse**          | `This is my first payment` | The input text where the search will be performed. |
| **Text to find**           | `Payment`           | The specific word or phrase to locate within the text. |
| **Is regular expression**  | `Disabled`          | Determines if the text to find is a regex pattern. (Disabled means exact matching is used.) |
| **Start parsing at position** | `0`               | The position in the text where the search should begin. |
| **First occurrence only**  | `Enabled`           | If enabled, it extracts only the first occurrence of the searched text. |
| **Ignore case**            | `Enabled`           | If enabled, the search is **case-insensitive** (e.g., "Payment" would match "payment" or "PAYMENT"). |

---

## **Example Use Cases**

### **Example 1: Finding a Keyword**

#### **Input**

```plaintext
This is my first payment
```

#### **Output**

```plaintext
"Payment"
Use Case: Extracting specific words from text.
```

---

## **Summary**

- **Finds the word** `"Payment"` in `"This is my first payment"`.
- **Case-insensitive search** ensures `"payment"` is matched.
- **Extracts only the first occurrence** (even if multiple exist).
- **Does not use regex**, so it looks for an exact match.
