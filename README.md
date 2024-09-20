# SAP ABAP Training: Practical Activities

This repository contains topics covered in the ABAP training, featuring practical activities that cover the following concepts:

- Tables, Structures, Data Elements, Domain, Views
- Search Help, SM30, Report Program, Internal Table, Work Area, Sub-routines
- SQL Operations: SELECT, INSERT, UPDATE, MODIFY, DELETE
- ABAP Objects: Classes, Interfaces, Objects, Methods, Events
- ALV, ALV_GRID, Function Module, Module Pool, Batch Input, BAPI, BADI, SAP Script, Smart Forms

## Final Training Activities

### Activity 1: Custom Table Creation
Create a custom Z table to record purchase orders sent to suppliers. This table will be populated via a function module that should be created and maintained using the SM30 transaction for updates.

**Knowledge Applied:**
- Creation of custom Z table, views, function modules
- Transactions: SE11, SM30, SE54, SE37, SE93

---

### Activity 2: Generate Purchase Order using BAPI
Develop a program to generate a purchase order using BAPI. The data for creating the purchase order should be read from an Excel spreadsheet based on a provided template.

**Knowledge Applied:**
- Report standardization, INCLUDEs, POHEADER and POHEADERX structures
- BAPI, ALV, Transactions SE80 and SE37

---

### Activity 3: Purchase Order Data Report
Create a report to display purchase order data through an ALV, using parameters provided in the selection screen. A hotspot (link) should be created in the EBELN field within the ALV, which when clicked will automatically open transaction ME23N.

**Knowledge Applied:**
- Report standardization (REPORT ZXX), INCLUDEs (ZXX_TOP, ZXX_SEL, ZXX_DEF, ZXX_IMP)
- Class and method implementation, SELECT statements, ALV
- Data types, type table, Transactions SE93, SE80, and ME23N

---

### Activity 4: Import Data from Excel
Create a program to import data from an Excel spreadsheet and insert it into a Z table, displaying the data in an ALV.

**Knowledge Applied:**
- Report organization (REPORT ZXX), INCLUDEs (ZXX_TOP, ZXX_SEL, ZXX_IMP)
- Data types, type table, SELECTION-SCREEN
- `cl_gui_frontend_services=>file_open_dialog`, function 'GUI_UPLOAD'

---

### Activity 5: Vehicle Registration Automation
Develop a program to automate vehicle registration.

**Knowledge Applied:**
- Module Pool for the screen and ALV_GRID for data display
- TABLE, VIEW, SEARCH HELP, Transactions SE11, SM30, and SE80

---

### Activity 6: Vehicle Revision Data Report
Create a report with vehicle revision data.

**Knowledge Applied:**
- Report standardization (REPORT ZXX_REL), INCLUDEs (ZXX_REL_TOP, ZXX_REL_SEL, ZXX_REL_FORMS)
- FUNCTION 'SSF_FUNCTION_MODULE_NAME', and SmartForms transaction to create and format the report output.
