# Wait for Text on Terminal Session

## Description

This screenshot demonstrates an interface for waiting until specific text appears in an active terminal session. Users can specify the text to wait for, whether it’s a regular expression or plain text, and define the location (e.g., screen or field) where the text should appear.

![alt text](../../assests/app-integrations/assests%20terminal%20emulation/wait-for-text-on-terminal-session.png)

---

## Configuration

### Terminal Session

- **Field**: Select the terminal session to monitor for the text.

### Text to Wait For

- **Field**: Enter the text or regular expression to wait for.

### Regular Expression

- **Option**: Specify whether the text is a regular expression (e.g., enable for pattern matching).

### Wait for Text Location

- **Option**: Choose where to wait for the text (e.g., `Screen` or a specific field).

### Get Field By

- **Option**: Specify how to identify the field (e.g., by `Label`).

### Label

- **Field**: Enter the label associated with the field (if applicable).

### Index

- **Field**: Specify the index of the field (if applicable).

### Row

- **Field**: Enter the row number to monitor (if applicable).

---

## Summary

This tool is useful for automating interactions with terminal-based applications by waiting for specific text to appear on the screen or in a field. It supports both plain text and regular expressions, providing flexibility for complex scenarios.
