# Write Text from File

## Description

The **Write Text From File** action allows users to write or append text content to a specified file.

![Write Text to File UI](write-text-from-file.png)

## Fields and Options  

### 1. **File Path** *(Required)* 🛈

- Specify the file path where the text should be written.  
- If the file does not exist, it may be created based on the chosen settings.  

### 2. **Text to Write** *(Required)* 🛈

- Enter the text content that should be written to the file.  
- This field does not support formatting, only plain text.  

### 3. **Append New File** *(Optional)* 🛈

- If a new file is created, additional text can be appended using this field.  

### 4. **If File Exists** *(Required)* 🛈

- Defines what happens if the file already exists. Options include:  
  - **Overwrite existing content** – Replaces the current file content.  
  - **Append to existing content** – Adds new text at the end of the file.  
  - **Do nothing** – Leaves the file unchanged.  

### 5. **Encoding** *(Optional)* 🛈

- Defines the character encoding used to write the file.  
- Default: **UTF-8** (recommended for most cases).  
- Other options include ASCII, ISO-8859-1, etc.  

## Use Cases

- Saving logs, reports, or generated text files.  
- Updating configuration files dynamically.  
- Appending data to an existing text-based dataset.  

## Important Notes

- If **overwrite** is selected, existing content will be permanently lost.  
- Ensure the correct **file path** is specified to prevent accidental modifications.  
- Using the **append** option helps maintain historical data in logs or reports.  

## Summary

The **Write Text to File** action is a powerful tool for writing, updating, and appending text content efficiently.
