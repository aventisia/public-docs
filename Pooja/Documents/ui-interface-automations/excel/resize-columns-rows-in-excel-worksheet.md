# Resize Columns/Rows in Excel Dialog

## Description

This section details the user interface of a dialog window used for resizing columns or rows in an Excel workbook. The dialog is titled **"Resize columns/rows in Excel"** and provides options for selecting an Excel instance, target, range, and resize type.

![Resize column Rows](../../assests/ui-interface-automations/assests%20excel/resize-columns-rows-in-Excel-worksheet.png)

### Dialog Layout

- **Title Bar**:
  - The title **"Resize columns/rows in Excel"** is displayed at the top in bold, dark font, clearly indicating the dialog's purpose.
  - A close button (represented by an "X") is located in the top-right corner, allowing the user to dismiss the dialog without saving changes.

- **Form Fields**:

  - **Excel Instance Field**:
    - Label: "Excel instance"
    - Type: Likely a dropdown or input field (visually appears as a text input with a border).
    - Additional Element: An information icon (ℹ) is positioned to the right of the label, possibly providing a tooltip or help text about selecting an Excel instance.
    - Current State: The field is empty, indicating that the user needs to select or input an Excel instance (e.g., a specific workbook or session).

  - **Resize Target Field**:
    - Label: "Resize target"
    - Type: Dropdown menu with a downward arrow, indicating multiple selectable options.
    - Current Selection: Set to "Column," suggesting that the user intends to resize columns (other options might include "Row").
    - Additional Element: An information icon (ℹ) is present, likely offering guidance on the target selection.

  - **Selection Range Field**:
    - Label: "Selection range"
    - Type: Dropdown menu with a downward arrow, indicating multiple selectable options.
    - Current Selection: Set to "Single," implying that the resize operation will apply to a single column or row (other options might include "Multiple" or "All").
    - Additional Element: An information icon (ℹ) is present, potentially explaining the range selection.

  - **Column Field**:
    - Label: "Column"
    - Type: Likely a dropdown or input field (visually appears as a text input with a border).
    - Additional Element: A red asterisk (*) indicates that this field is mandatory, and an information icon (ℹ) provides further context.
    - Current State: The field is empty, requiring the user to specify a column (e.g., "A", "B", etc.).

  - **Resize Type Field**:
    - Label: "Resize type"
    - Type: Dropdown menu with a downward arrow, indicating multiple selectable options.
    - Current Selection: Set to "Fit," suggesting that the resize operation will adjust the column/row to fit its content (other options might include "Custom" or "Default").
    - Additional Element: An information icon (ℹ) is present, likely explaining the resize type options.
