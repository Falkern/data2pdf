# Data2PDF

A command-line tool for generating PDF reports from CSV files, Excel spreadsheets, or databases using Python. This project leverages popular libraries such as Pandas, SQLAlchemy, FPDF, and OpenPyXL to read data and create formatted PDF reports.

## Features

- Read data from CSV files
- Read data from Excel files
- Fetch data from databases using SQL queries
- Generate PDF reports from the data

## Requirements

- Python 3.x
- pandas
- sqlalchemy
- fpdf
- argparse
- logging
- openpyxl
- tqdm

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/Falkern/data2pdf.git
   ```
2. Navigate to the project directory:
   ```sh
   cd reports
   ```
3. Install the required packages:
   ```sh
   pip install -r requirements.txt
   ```

## Usage

To generate a PDF report, run the script with the appropriate arguments:

- From a CSV file:
  ```sh
  python report_generator.py --csv path/to/yourfile.csv --output report.pdf
  ```
- From an Excel file:
  ```sh
  python report_generator.py --excel path/to/yourfile.xlsx --output report.pdf
  ```
- From a database query:
  ```sh
  python report_generator.py --db "your_connection_string" --query "your_sql_query" --output report.pdf
  ```

## Example

```sh
python report_generator.py --csv data/sample.csv --output report.pdf
```
