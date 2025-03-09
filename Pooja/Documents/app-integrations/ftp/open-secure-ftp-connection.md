# Open Secure FTP Connection

## Description

This screenshot demonstrates an interface for opening a secure FTP (SFTP) connection to a remote server. Users can specify the host, port, authentication method, and other connection details.

![alt text](../../assests/app-integrations/assests%20ftp/open-secure-ftp-connection.png)

---

## Configuration

### Host

- **Field**: Enter the host address of the SFTP server (e.g., `sftp.example.com`).

### Port

- **Field**: Specify the port number for the SFTP connection (default is `22`).

### Secure FTP Protocol

- **Option**: Select the protocol (e.g., `SFTP`).

### Authentication Method

- **Option**: Choose the authentication method (e.g., `Username` and `Password`).

### Username

- **Field**: Enter the username for authentication.

### Password

- **Field**: Enter the password for authentication.

### Timeout

- **Field**: Set the connection timeout in seconds (e.g., `10`).

---

## Output

- **SFTP Connection**: A secure FTP connection object for interacting with the remote server.

---

## Example: Input and Output

### Scenario

You want to connect to an SFTP server with the following details:

- **Host**: `sftp.example.com`
- **Port**: `22`
- **Username**: `user123`
- **Password**: `password123`
- **Timeout**: `10` seconds

---

### Input

- **Host**: `sftp.example.com`
- **Port**: `22`
- **Secure FTP Protocol**: `SFTP`
- **Authentication Method**: `Username` and `Password`
- **Username**: `user123`
- **Password**: `password123`
- **Timeout**: `10`

---

### Output

- **SFTP Connection**: A connection object is created, allowing you to interact with the SFTP server (e.g., list files, upload/download files).

---

## Summary

This tool is useful for establishing secure FTP (SFTP) connections to remote servers. It supports authentication via username and password, and allows configuration of connection details like host, port, and timeout.
