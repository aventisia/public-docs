# Upload File(s) to FTP

## Description

This action allows you to **upload local files** to a remote FTP server. It's useful when automating data exports, backups, or sharing files with external parties.

---
![Upload dile to FTP](../../assests/app-integrations/assests%20ftp/upload-file(s)-to-ftp.png)

## Fields Explained

| Field | Description |
|-------|-------------|
| **FTP connection** | Select or define your FTP connection here. This contains details like FTP hostname, username, password, and port. |
| **File(s) to download** | (Should actually be labeled **File(s) to upload**) - Specify the full path(s) to the file(s) you want to upload from your local machine. You can also use wildcards, e.g., `*.csv`, `report_*.xlsx`. |
| **RemoteLocation** | Enter the **destination folder path** on the FTP server where the files should be uploaded. Example: `/uploads/reports/` |
| **Transfer type** | Select the appropriate mode:<br> - `Auto`: Let the system choose<br> - `Binary`: Best for images, PDFs, videos<br> - `ASCII`: Best for plain text, `.csv`, `.txt` |
| **If file exists** | Decide what happens if a file with the same name exists on the FTP server:<br> - `Overwrite`: Replace the file<br> - `Skip`: Leave the existing file<br> - `Rename`: Rename the new file to avoid overwriting |

---

## Use Cases

- Automate daily file uploads to partners or clients.
- Backup logs or generated reports to a secure FTP server.
- Schedule periodic uploads for data synchronization between systems.

---

## Example Configuration

Let’s say you want to upload all `.csv` files from `D:\Exports\` to the `/data/monthly/` folder on your FTP server:

- **FTP connection**: `MySecureFTP`
- **File(s) to upload**: `D:\Exports\*.csv`
- **RemoteLocation**: `/data/monthly/`
- **Transfer type**: `ASCII`
- **If file exists**: `Rename`

This configuration will upload all matching files without overwriting existing ones, ensuring your previous data stays intact.
