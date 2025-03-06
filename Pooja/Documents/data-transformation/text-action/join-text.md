# **Join Text Operation**

## **Description**

The **Join Text** operation concatenates elements from a list into a single string, separated by a specified delimiter.

---
![alt text](join-text-1.png)

## **Configuration Options**

| Parameter                            | Value        | Description |
|--------------------------------------|-------------|-------------|
| **Specify the list to join**         | `var_List1` | The list containing elements to be joined. |
| **Delimiter to separate list items** | `Custom`    | The separator between concatenated list elements. |
| **Custom delimiter**                 | `;`         | The specified delimiter for joining the text. |

---

## **Effect**

- Combines **all elements** of the list into a single **joined string**.
- Uses the specified **custom delimiter** (`;` in this case) to separate elements.

---

## **Example Use Cases**

### **Example 1: Joining a List of Names**

#### **Input**

```python
var_List1 = ["Alice", "Bob", "Charlie"]
```

### **Output**

```python
Alice, Bob, Charlie
