# Empty Folder

## Description

The **Empty Folder** action removes all files and subfolders within a specified folder without deleting the folder itself.

![Empty Folder UI](empty-folder.png)

## Fields and Options  

### **1. Folder to Empty** *(Required)* 🛈

- Specify the full path of the folder to be emptied.
- Ensure the folder exists before execution.

### **2. On Error** *(Optional)*

- Define the action to take if an error occurs (e.g., folder not found, permission issues).

## Use Cases

- Clearing temporary or cache directories.
- Resetting workspace folders for automation.
- Removing old log files while keeping the folder structure intact.

## Important Notes

- **Files and subfolders will be permanently deleted**—ensure no important data remains.
- The action may fail if files are in use or permissions restrict deletion.
- Hidden or system-protected files may not be removed.

## Summary

The **Empty Folder** action is useful for managing and cleaning up directories while preserving folder structures.
