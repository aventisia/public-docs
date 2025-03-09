# Invoke FTP Command

## Description

This screenshot demonstrates an interface for invoking a custom FTP command on a remote server. Users can specify the FTP connection and the expected valid reply codes. The output includes the actual reply code and text returned by the FTP server.

![alt text](../../assests/app-integrations/assests%20ftp/invoke-ftp-command.png)

---

## Configuration

### FTP Connection

- **Field**: Select the active FTP connection to use for the command.

### Valid Reply Code(s)

- **Field**: Enter the expected valid reply code(s) from the FTP server (e.g., `200` for success).

---

## Output

### ReplyCode

- **Description**: The actual reply code returned by the FTP server. This applies only to simple FTP or FTPS connections.

### ReplyText

- **Description**: The text message returned by the FTP server in response to the command.

---

## Summary

This tool is useful for sending custom FTP commands to a remote server and retrieving the server's response. It allows users to validate the success of the command using reply codes and analyze the server's response text.
