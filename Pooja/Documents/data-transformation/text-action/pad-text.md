# **Pad Text**

## **Description**

The **Pad Text** operation allows you to add **extra characters or words** to a given text string to meet a **specific length requirement**. Padding is useful for **text formatting, alignment, and ensuring uniformity** in structured data.

This operation supports **three types of padding**:

- **Left Padding**: Adds the specified padding characters **at the beginning** of the text.  
- **Right Padding**: Adds the specified padding characters **at the end** of the text.  
- **Both-Side Padding**: Adds padding characters **equally on both sides** of the text.  

Padding is particularly useful in **text-based interfaces, report generation, structured logs, and UI elements** where maintaining a uniform appearance is necessary.

![alt text](../../assests/data-transformation/assests%20text-action/pad-text.png)

---

## **Input Parameters**

| Parameter          | Value           | Description |
|-------------------|----------------|-------------|
| **Text to Pad**   | `Hello World`   | The original text that needs to be padded. |
| **Pad**          | `Right`          | Defines whether to pad on the left, right, or both sides. |
| **Text for Padding** | `of RPA`      | The text used for padding. |
| **Total Length**  | `10`            | The total desired length of the padded text. |

---

## **Output**

| Parameter   | Description |
|------------|-------------|
| **PaddedText** | The new text with the applied padding, ensuring it meets the specified total length. |

---

## **Example Use Cases**

### **Example 1: Padding to the Right**

#### **Scenario**  

A user wants to **pad** `"Hello World"` on the **right** with `"of RPA"`, up to a **total length of 10**.

#### **Configuration**

- **Text to Pad:** `Hello World`
- **Pad:** `Right`
- **Text for Padding:** `of RPA`
- **Total Length:** `10`

#### **Result** Hello World of RPA

---

## **Summary**

- Adds **padding** to the specified text as per the configuration.
- Helps in **text formatting, alignment, and standardization**.
- Ensures consistency in **data fields**, especially in **structured logs, reports, and UI elements**.
- Useful when preparing text for **fixed-width display environments**, such as command-line interfaces or legacy systems.
