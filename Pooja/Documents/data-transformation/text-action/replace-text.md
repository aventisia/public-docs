# **Replace Text**

## **Description**

The **Replace Text** operation allows you to search for a specific substring within a given text and replace it with another value.

---

![alt text](../../assests/data-transformation/assests%20text-action/replace-text.png)

## **Configuration Options**

| Parameter                                    | Value              | Description |
|----------------------------------------------|--------------------|-------------|
| **Text to parse**                            | `This is my first payment` | The input text where the replacement will occur. |
| **Text to find**                             | `Payment`          | The word or phrase to be replaced. |
| **Use regular expressions for find and replace** | `Disabled`   | If enabled, regex patterns can be used to match complex text patterns. |
| **Ignore case**                              | `Enabled`          | If enabled, it replaces text in a **case-insensitive** manner. |
| **Replace with**                             | `Transaction`      | The replacement text. |
| **Activate escape sequence**                 | `Disabled`         | If enabled, special sequences (e.g., `\t` for tab) would be processed in the replacement text. |

---

## **Example Use Cases**

### **Example 1: Simple Word Replacement**

#### **Input**

```plaintext
This is my first payment
```

### **Output**

```plaintext
This is my first transaction

Use Case: Renaming words in text dynamically.
```

---

## **Summary**

- Finds `"Payment"` in `"This is my first payment"`.
- **Case-insensitive replacement** ensures `"payment"` or `"PAYMENT"` are also matched.
- Replaces it with `"Transaction"`, modifying the text to `"This is my first transaction"`.
- **No regex used**, so only exact word matches apply.
