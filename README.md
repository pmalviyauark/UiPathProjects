# UiPathProjects
This repository showcases a collection of automation solutions built using UiPath Studio. It includes a variety of real-world use cases and is designed to demonstrate the practical application of Robotic Process Automation (RPA) through workflows that are scalable, efficient, and aligned with business goals.

## Project 1 - Atlas Invoice Processing Project
This project demonstrates an end-to-end intelligent automation solution built on the UiPath REFramework to extract, validate, and process invoices using UiPath Document Understanding and OmniPage OCR. The automation is designed to read semi-structured invoice PDFs, extract key fields (like invoice number, invoice date, address, email, line items, etc.), and post the data into downstream systems or databases.

**Key Features:**
* Document Understanding Framework integration for invoice classification and data extraction
* Uses OmniPage OCR engine for high-accuracy text recognition from scanned PDFs
* Built on REFramework, ensuring modularity, exception handling, and transaction management
* Includes validation station support for human-in-the-loop review of low-confidence fields
* Organizes input, processed, and rejected invoices into separate folders with detailed logging
* Outputs extracted data to structured formats (Excel/CSV/Database) for further processing

## Project 2 - New Supplier Registration Project
This project automates the end-to-end supplier registration and data management workflow on the [Visit RPASamples Supplier Portal](https://www.rpasamples.com) using UiPath's Robotic Enterprise Framework (REFramework). It performs web-based data entry, file upload, dynamic date selection, record verification, email communication, CSV data cleansing, and structured data export to Excel categorized by industry, all while handling errors, retries, and logging as per REFramework best practices.

**Key Features:**
* Automated supplier registration through web form interaction including text entry, dropdown selection, checkbox validation, and file upload
* Dynamic date handling to select a date 40 days before the current date in the form
* Automated record verification by searching with the external name and capturing browser screenshots
* Email automation to send the captured screenshot as an attachment via SMTP to a configured recipient
* Automated CSV report download and processing, named dynamically with the user’s name and current date
* Duplicate data removal and structured output of cleaned records into industry-specific Excel sheets
