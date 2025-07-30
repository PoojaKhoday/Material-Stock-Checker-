Material Stock Checker ALV Report (ZMATERIAL_STOCK_CHECKER_PPK)

Project Overview
This SAP ABAP project is an ALV report to display material stock details such as:
- Material Number (MATNR)
- Material Type (MTART)
- Industry Sector (MBRSH)
- Plant (WERKS)
- Storage Location (LGORT)
- Current Stock (LABST)
- Stock in Transfer (UMLME)
- Stock in Quality Inspection (INSME)
The report retrieves data using INNER JOIN from the MARA and MARD tables and displays it in an ALV Grid with auto column optimization and a zebra pattern for better readability.

SAP Tables Used
- MARA – General Material Data
- MARD – Storage Location Stock Data

Features
Selection Screen to filter materials by Material Number (MATNR)
- ALV Grid Display with:
- Auto column width optimization
- Zebra line pattern for better readability
- Custom Top-of-Page Header using 'REUSE_ALV_COMMENTARY_WRITE'
- Displays success or error message based on records fetched
- Center aligned data for a cleaner view

Learning Outcomes
By implementing this project, you will learn:
- Fetching material and stock details using table joins
- Building dynamic ALV reports using 'REUSE_ALV_GRID_DISPLAY'
- Creating and populating a Field Catalog (SLIS_FIELDCAT_ALV)
- Applying ALV layout features like zebra pattern and column width optimization
- Adding custom report headers in ALV reports

