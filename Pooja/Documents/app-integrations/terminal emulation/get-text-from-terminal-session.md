# Get Text from Terminal Session

## Description

This screenshot demonstrates an interface for extracting text from an active terminal session. Users can specify the source of the text (e.g., the entire screen or a specific field) and configure additional parameters such as label, index, text length, and row.

![alt text](../../assests/app-integrations/assests%20terminal%20emulation/get-text-from-terminal-session1.png)

![alt text](../../assests/app-integrations/assests%20terminal%20emulation/get-text-from-terminal-session2.png)

---

## Configuration

### Terminal Session

- **Field**: Select the terminal session from which to extract text.

### Get Text From

- **Option**: Choose the source of the text (e.g., `Entire screen`).

### Get Field By

- **Option**: Specify how to identify the field (e.g., by `Label`).

### Label

- **Field**: Enter the label associated with the field (e.g., `pspfitnessclub`).

### Index

- **Field**: Specify the index of the field (e.g., `-1` for no specific index).

### Text Length

- **Field**: Define the length of the text to extract (e.g., `7` characters).

### Row

- **Field**: Enter the row number from which to extract the text (e.g., `0`).

### Column

- **Field**: Enter the column number from which to extract the text (e.g., `1`).

---

## Output

- **TerminalText**: The text extracted from the specified column.

---

## Summary

This tool is useful for extracting specific text from a terminal session, whether from the entire screen or a particular field. It provides flexibility in defining the source and scope of the text, making it ideal for automating interactions with terminal-based applications.
