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
