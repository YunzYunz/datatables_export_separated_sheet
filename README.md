

---

# DataTables Example

This project demonstrates a DataTables implementation with various features including filtering, pagination, custom styling, and Excel export functionality.

### Features:
- **Filtering**: Use the dropdown to filter data based on selected columns (`Position Karyawan`, `Office`, `Salary`).
- **Pagination**: Custom pagination controls with options to navigate through pages.
- **Export to Excel**: Export selected rows to Excel with customized sheets based on column selections.
- **Search**: Search functionality to filter data within the table based on input.

### Setup:
1. Include the necessary CSS and JavaScript libraries:
   - jQuery, DataTables, Select2 for dropdown, Buttons for Excel export.
2. Define table structure (`<table>`), including headers and body rows.
3. Initialize DataTables with customization:
   - Custom pagination (`full_numbers_no_ellipses`), page length selection.
   - Disable sorting on specific columns (`checkbox-header`, `Age`).
4. Implement custom functionalities:
   - Populate and handle filtering with Select2 dropdown.
   - Handle row checkboxes for selection.
   - Custom export to Excel feature using DataTables buttons and XLSX.js library.
   - Search functionality to filter table rows based on user input.

### Usage:
- **Filtering**: Select options from the dropdown to filter data by specific columns.
- **Pagination**: Navigate through pages using the pagination controls.
- **Export to Excel**: Click 'Export Selected to Excel' to generate and download an Excel file with selected rows.
- **Search**: Enter keywords in the search input to filter rows based on the input.

### Notes:
- Ensure all necessary libraries are included and paths are correctly set for CSS and JavaScript files.
- Customize column visibility, sorting, and other DataTables features as per project requirements.

### Dependencies:
- jQuery (v3.5.1)
- DataTables (v1.11.4)
- Select2 (v4.0.13)
- Buttons (v2.2.3)
- XLSX.js (v0.16.2)

### License:
This project is licensed under [MIT License](LICENSE).

---

