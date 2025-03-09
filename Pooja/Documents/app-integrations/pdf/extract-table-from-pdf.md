# Extract Tables from PDF  

## **Description**

This interface allows users to extract tables from a PDF file while providing options for handling multi-page tables and column names.

![alt text](../../assests/app-integrations/assests%20pdf/extract-table-from-pdf.png)

---

## PDF File

**(Required)** Upload the PDF file from which you want to extract tables.  

---

## Page(s) to Extract

Select the pages from which tables should be extracted.

- **All** – Extracts tables from the entire document.  
- **Single Page** – Extracts tables from a specific page.  
- **Page Range** – Extracts tables from a defined range of pages.  

---

## From Page Number / To Page Number

Define a range of pages to extract tables from.  

---

## Merge Tables that Cross Page Margins

Enable this option to merge tables that span multiple pages.

- **ON**: Tables that continue across page breaks are merged.
- **OFF**: Tables remain separate per page.  

---

## First Line Contains Column Names

Enable this option if the first row of the extracted table represents column names.

- **ON**: First row is treated as column headers.
- **OFF**: First row is treated as table data.  

---

**🔔 Note:** Ensure the PDF contains properly formatted tables for the best extraction results.
