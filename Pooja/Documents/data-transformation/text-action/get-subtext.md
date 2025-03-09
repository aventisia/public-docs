# **Get Subtext**

## **Description**

This operation extracts a portion of text from a given string based on a specified starting position and length.

![alt text](../../assests/data-transformation/assests%20text-action/get-subtext.png)

## **Input Parameters**

| Parameter        | Value        | Description |
|-----------------|-------------|-------------|
| **Original Text** | `Pune`      | The full text from which a substring will be extracted. |
| **Start Index**  | `Start of text` | Defines where the extraction begins (e.g., start, specific index). |
| **Length**       | `Number of chars` | Defines the extraction length method (characters, words, etc.). |
| **Number of chars** | `2` | The number of characters to extract from the start index. |

## **Output**

| Parameter   | Description |
|------------|-------------|
| **Subtext** | The retrieved substring based on the provided parameters. |

## **Example Use Case**

- **Scenario:** A user wants to extract the **first two characters** of a city name.
- **Configuration:**
  - Original Text: `Pune`
  - Start Index: `Start of text`
  - Number of Characters: `2`
- **Result:** The output will be:  Pu

## **Summary**

- Extracts part of a given text.
- Can be used for **data parsing, text processing, and string manipulation**.
