The Data to PDF Converter is a Python script that reads data from an Excel file and generates individual PDF documents for each row of data. It utilizes the pandas library to read the Excel file and the FPDF library to create the PDF documents.

Clone the repo:

``git clone https://github.com/your-username/data-to-pdf-converter.git``

Install the dependencies:

``pip install pandas fpdf``

Prepare your data:

- Create an Excel file named data.xlsx containing the data to be converted to PDF.
- Ensure that the first column contains unique identifiers (e.g., names) for each row.

Run the script:

``python data_to_pdf_converter.py``
