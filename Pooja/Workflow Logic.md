# Flowbuilder Actions- Workflow Logics
Core actions to build the foundation of any automation flow

 ![image](https://github.com/user-attachments/assets/f9b58447-4863-4ebc-b10f-eb4b71fd7fa4)


Here is an overview of the workflow logic, with a focus on the available building blocks:

  ![image](https://github.com/user-attachments/assets/8706c36e-f822-48be-9ae5-71a50cb4f536)


## Variables Actions

These building blocks manipulate and manage data within the workflow.

### **Truncate Number**  :  
 The **Truncate Number** action is used to manipulate numeric values by either extracting specific parts of the number or rounding it to a defined precision. This operation does not perform standard rounding (where a number is rounded up or down based on its value), but instead truncates (cuts off) the number at a specified decimal place or integral digit.

 There are a few key aspects of this operation:

 1. **Extracting Integral Digits**:  
    - If you want to isolate only the whole number part of a decimal, you can use truncation to remove the fractional (decimal) part. For example, truncating  `23.6789` to 0 decimal places would result in `23`.

 2. **Extracting Fractional Digits**:  
   - If you need to isolate only the fractional part of a number, truncation can remove the integral part. For example, truncating `23.6789` to 3 decimal places would result in `0.678`.

 3. **Rounding to a Specific Decimal Place**:  
    - Truncating can be used to "round down" a number to a particular number of decimal places without rounding up. For example, truncating `23.6789` to 2 decimal places results in `23.67`, as the digits after the second decimal place are simply cut off without rounding.

 #### Example Scenarios:
 - **Truncate to 0 Decimal Places**:  
   `Truncate(23.6789, 0)` → `23`  
   This removes the decimal part completely.
 
 - **Truncate to 2 Decimal Places**:  
   `Truncate(23.6789, 2)` → `23.67`  
   This keeps only the first two decimal places.
 
 - **Truncate to 3 Decimal Places**:  
   `Truncate(23.6789, 3)` → `23.678`  
   This keeps the first three decimal places and removes anything after.
 
 #### Key Points:
 - **Non-Rounding Behavior**: Truncating is different from rounding because it will never round a number up. For example, truncating `2.999` to 1 decimal place results in `2.9`, rather than rounding it to `3.0`.
   
 - **Precision Control**: Truncating allows you to have precise control over the number of digits you want to keep, especially useful in cases where rounding might introduce undesirable approximations.
 
 In summary, the **Truncate Number** function is a way to manipulate and control the decimal or integral parts of a number, offering consistent and non-rounding results for specific use cases in calculations.

- **Generate Random Number**:  
  Creates one or multiple random numbers within a defined range.

- **Clear List**:  
  Empties the contents of a list.

- **Remove Item from List**:  
  Deletes one or multiple items from a list.

- **Sort List**:  
  Arranges list items in ascending or descending order (items must be of the same type).

- **Shuffle List**:  
  Randomizes the order of items in a list.

- **Merge Lists**:  
  Combines two lists into a single list.

- **Reverse List**:  
  Inverts the order of items within a list.

- **Remove Duplicate Items from List**:  
  Eliminates duplicate items, ensuring each item appears only once.

- **Find Common List Items**:  
  Compares two lists and creates a new list containing only the common items.

- **Subtract Lists**:  
  Compares two lists and creates a new list containing items present in the first list but not the second.

- **Retrieve Data Table Column into List**:  
  Converts the contents of a data table column into a list.

- **Convert JSON to Custom Object**:  
  Transforms JSON data into a custom object.

- **Convert Custom Object to JSON**:  
  Transforms a custom object into a JSON string.

- **Add New Item to List**:  
  Appends a new item to an existing list.

- **Create New List**:  
  Creates an empty list.

- **Increase Variable**:  
  Increments the value of a variable by a specified amount.

- **Decrease Variable**:  
  Decrements the value of a variable by a specified amount.

- **Run Power Fx Expression**:  
  Executes a provided Power Fx expression.

- **Set Variable**:  
  Assigns a value to a new or existing variable, creating a new variable or overwriting a previous one.

## DataTable Actions

- **Create new data table**:  
  Creates a new data table variable.

- **Insert row into data table**:  
  Inserts a row at the end or before a specific index value.

- **Delete row from data table**:  
  Deletes a data table row at the corresponding row index.

- **Update data table item**:  
  Updates a data table row item in a defined column.

- **Find or replace in data table**:  
  Finds and/or replaces data table values.

- **Insert column into data table**:  
  Inserts a column at the end or before a specific index value.

- **Delete column from data table**:  
  Deletes a data table column at the specified column index or by column name.

- **Delete empty rows from data table**:  
  Deletes rows in the data table that have all of their cells empty.

- **Delete duplicate rows from data table**:  
  Deletes all rows that are duplicates based on matching data types in each column.

- **Clear data table**:  
  Deletes all rows of the data table, keeping the table headers unaffected.

- **Sort data table**:  
  Sorts the rows in ascending or descending order by the specified column, if all its values share the same data type.

- **Filter data table**:  
  Filters the rows of the data table based on applied rules.

- **Merge data tables**:  
  Merges two data tables together, specifying how to handle differences in the number of columns.

- **Join data tables**:  
  Joins two data tables based on the specified join rule.

- **Read from CSV text variable**:  
  Generates a data table from CSV text.

- **Convert data table to text**:  
  Converts a data table into CSV text format.

## Conditionals Actions

- **Conditional**:  
  Dispatches execution to different parts of the flow based on the value of the expression.

## Loops Actions

- **Loop**:  
  Iterates a block of actions for a specified number of times.

## Flow Control Actions

- **Comment**:  
  User comment.

- **End**:  
  Marks the end of a block.

- **End region**:  
  Marks the end of a group of actions.

- **Exit subflow**:  
  Exits the current subflow and returns to the point where it was called from.

- **Get last error**:  
  Retrieves the last error that occurred in the flow.

- **Go to**:  
  Transfers the flow of execution to a designated point, indicated by a label.

- **Label**:  
  Acts as the destination of a 'go to' statement.

- **On block error**:  
  Marks the beginning of a block for handling errors in actions.

- **Region**:  
  Marks the start of a group of actions.

- **Run subflow**:  
  Runs a subflow with any required arguments.

- **Stop flow**:  
  Terminates the flow.

- **Wait**:  
  Pauses the execution of the flow for a specified number of seconds.

## Run Flow Actions

- **Run desktop flow**:  
  Runs a desktop flow that can receive input variables and might produce output variables. The parent flow will be paused until the desktop flow completes.

## HTTP Actions 

- **Download from web**:  
  Downloads text or a file from the web and stores it.

- **Invoke SOAP web service**:  
  Invokes a method from a SOAP web service.

- **Invoke web service**:  
  Invokes a web service and stores the response text.
