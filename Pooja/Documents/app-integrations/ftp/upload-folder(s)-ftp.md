# 📁 Upload Folder(s) to FTP

## Description

This action enables the **upload of entire folders** from your local system to a specified directory on an FTP server. It's ideal for sending grouped data, media assets, or backups.

---
![Upload Folder to FTP](../../assests/app-integrations/assests%20ftp/upload-folder(s)-ftp.png)

## Fields Explained

| Field | Description |
|-------|-------------|
| **FTP connection** | Select or create an FTP connection containing the hostname, port, username, and password required to connect to the remote server. |
| **File(s) to download** | Despite the label, this actually refers to the **folder(s) to upload** from your local environment. You can enter a folder path like `C:\Reports\Monthly` or use dynamic expressions. |
| **RemoteLocation** | Define the destination folder path on the FTP server. Example: `/uploads/2024/April`. All the contents from your selected folder(s) will be uploaded to this location. |

---

## Use Cases

- Upload batches of generated reports grouped in folders.
- Transfer media folders (e.g., images, videos) to a content distribution FTP server.
- Send compressed archives or backups of folders to off-site FTP storage.

---

## Example Configuration

You want to upload a folder called `C:\Backups\ProjectAlpha` to your FTP server at `/project_uploads`:

- **FTP connection**: `AlphaFTP`
- **File(s) to download**: `C:\Backups\ProjectAlpha`
- **RemoteLocation**: `/project_uploads`

This will upload all contents (and subfolders) inside `ProjectAlpha` to the remote directory.
