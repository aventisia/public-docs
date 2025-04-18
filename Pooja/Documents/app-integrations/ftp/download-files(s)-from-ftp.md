# Download file(s) from FTP

## Description

This action allows you to **retrieve one or more files** from a remote FTP server and store them locally in a specified folder. It's especially useful for automating data intake from external sources like vendors, clients, or other systems.

![Download file from FTP](../../assests/app-integrations/assests%20ftp/download-files(s)-from-ftp.png)
---

## Fields Breakdown

| Field | Description |
|-------|-------------|
| **FTP connection** | Select or provide your **FTP connection** here. This includes credentials and connection info such as host, port, username, and password. |
| **Download into folder** | Specify the **local folder** path where the downloaded files should be saved. Example: `C:\Users\YourName\Downloads\FTP_Files` |
| **File(s) to download** | Enter the **exact filename(s)** or use wildcards for bulk download:<br>- `report.csv`<br>- `*.txt` (all `.txt` files)<br>- `2025_*_sales.xlsx` |
| **Transfer type** | Choose how the file should be transferred:<br>- `Auto` (automatically selects Binary or ASCII)<br>- `Binary` (used for images, videos, PDFs, etc.)<br>- `ASCII` (used for text files like `.csv`, `.txt`) |
| **If file exists** *(optional dropdown below)* | Controls what happens if a file with the same name exists in the local folder:<br>- `Overwrite`<br>- `Skip`<br>- `Rename` |

---

## Use Cases

- Automated report downloads from vendor FTP servers.
- Syncing configuration or data files nightly.
- Moving files for archival or analysis from FTP servers into your local system or workflows.

---

## Example

Let’s say you want to download all `.csv` files from your FTP into `D:\Reports\`:

- **FTP connection**: `MyFTPConnection`
- **Download into folder**: `D:\Reports\`
- **File(s) to download**: `*.csv`
- **Transfer type**: `Binary`
- **If file exists**: `Overwrite`

This setup will fetch every `.csv` file from the FTP and replace any existing ones in the folder.
