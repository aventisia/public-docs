# Filter Data Table

## Description

This dialog is used to apply filters to an existing data table, producing a new filtered version based on specified criteria.

![Filter Data Table UI](../../assests/workflow-logics/assests%20datatable/filter-data-table.png)

---

## Fields and Options

### **1. Data Table**

- **Purpose:** Selects the source data table to filter.
- **Type:** Existing `DataTable` variable.
- **Requirement:** Must be populated with data to apply filters effectively.

### **2. Filters to Apply**

- **Purpose:** Specifies the filtering conditions.
- **Format Example:** `ColumnName = "Value"` or advanced expressions like `ColumnName > 100`
- **Supports:** Multiple filters and logical operators depending on the platform's filter syntax.

---

## Output (Expandable Section)

### **FilteredDataTable (Toggle Enabled)**

- **Purpose:** Stores the result of the filtering operation.
- **Default Name:** `FilteredDataTable`
- **Description:** "The generated data table after applying the filters"
- **Customizable:** Yes – you can rename this output variable.

---

## Common Use Cases

- Isolating rows based on conditions (e.g., date ranges, status flags)
- Cleaning data for downstream processing
- Preparing subsets for reporting or exporting
