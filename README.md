Input File:
PO numbers are read from an Excel or CSV file stored in a shared folder or local drive (e.g., input_PO_list.xlsx).

Selenium Automation:

Bot logs into the 1EDI Source portal.

Searches each PO from the input file.

Checks status and transmission details.


PO Categorization:

Tags each PO as Non-EDI PO, Needs Resolution, or Transmitted.

Logic is embedded to detect issues based on portal response.


Output File:
A new Excel file (e.g., PO_Status_Report.xlsx) is generated or updated with:

PO number

Status from portal

Category (Non-EDI / Needs Resolution / Transmitted)

Timestamp


Benefits:
Accurate, fast, and reduces manual work by ~80%
