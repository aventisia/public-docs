# Create New Data Table

## Description

This configuration dialog allows you to define a new empty data table for use in workflows. It serves as a container for structured data (rows and columns) that can be dynamically populated and manipulated.

![Create New Data Table UI](../../assests/workflow-logics/assests%20datatable/create-new-data-table.png)


## Fields and Options

### **1. Data Table**

- **Purpose:** Sets up the dimensions of the data table to be created.
- **Format:** Predefined as `0 Rows, 0 Columns` upon initial creation.
- **Note:** Additional rows and columns can be added programmatically later in the flow.

---

## Output (Expandable Section)

### **DataTable (Toggle Enabled)**

- **Purpose:** Defines the output variable where the new data table will be stored.
- **Default Name:** `DataTable`
- **Description:** "The new Data Table"
- **Customizable:** Yes – you can rename the variable as needed.

---

## Common Use Cases

- Creating a table structure to store results from loops or queries
- Populating with parsed data from files, web services, or user input
- Performing data transformations and exporting results
