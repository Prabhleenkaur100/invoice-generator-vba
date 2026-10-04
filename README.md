# Invoice Generator (Excel VBA)

An invoice generator built in Excel using VBA macros. It pulls customer and product details from master sheets, calculates GST automatically, and saves every invoice to a log.

## Sheets
- **Customers**: Customer ID, name, address, city, phone, email
- **Products**: Product ID, name, category, unit price, GST %
- **InvoiceLog**: Record of all generated invoices (Invoice No, Date, Customer, Product, Quantity, Price, GST %, Total)
- **InvoiceTemplate**: Printable invoice layout

## Features
- Auto-numbered invoices (INV-0001, INV-0002, ...)
- Customer and product details fetched from master data
- GST applied per product category (5%, 12%, 18%)
- Total = Quantity x Unit Price x (1 + GST %)
- Every invoice saved in InvoiceLog

## Tools Used
Excel, VBA / Macros

## How to Use
1. Download `Invoice_Generator_Data.xlsm`
2. Open it and click **Enable Macros**
3. Go to the InvoiceTemplate sheet and generate an invoice

## Author
Prabhleen Kaur
