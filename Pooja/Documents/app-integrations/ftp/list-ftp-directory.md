# List FTP Directory

## Description

This screenshot demonstrates an interface for listing the contents of a directory on an FTP server. Users can specify the FTP connection and the directory path to retrieve a list of directories and files.

![alt text](../../assests/app-integrations/assests%20ftp/list-ftp-directory.png)

---

## Configuration

### Connection

- **Field**: Select or specify the FTP connection to use.

### Path

- **Field**: Enter the directory path on the FTP server to list (e.g., `/documents`).

---

## Output

### Directories

- **Description**: A list of directories within the specified path.

### Files

- **Description**: A list of files within the specified path.

---

## Example: Input and Output

### Scenario

You want to list the contents of the `/documents` directory on an FTP server.

---

### Input

- **Connection**: `FTP_Connection_1` (pre-configured FTP connection).
- **Path**: `/documents`.

---

### Expected Output

- **Directories**:
/documents/reports
/documents/archives

- **Files**:
/documents/report1.pdf
/documents/report2.pdf
/documents/notes.txt

---

## Summary

This tool is useful for retrieving the contents of a directory on an FTP server. It provides a clear list of directories and files, making it easier to navigate and manage files on remote servers.
