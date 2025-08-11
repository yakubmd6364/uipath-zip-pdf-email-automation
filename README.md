# UiPath ZIP, PDF, and CSV Report Automation

This project is a UiPath workflow that automates ZIP file handling, moving and unzipping files, comparing PDFs with IDs from a CSV, generating a report, and emailing a summary. Sample PDF files are included for testing.

## Features

- Unzips files from source ZIP archives
- Moves and organizes files into target folders
- Compares PDF filenames/contents against IDs listed in a CSV file
- Generates a report (e.g., Excel) with comparison results
- Sends an automated email summary with the report attached
- Includes 12 sample PDF files for workflow testing

## Project Structure

- `Main Process.xaml` — Main workflow to control overall automation steps
- `project.json` — UiPath Studio project configuration
- `Report_YYYYMMDD.xlsx` — Example of generated report file
- `sample_pdfs/` — Contains 12 sample PDF files for testing
- `README.md` — Project documentation

## How to Use

1. Clone or download this repository to your local machine.
2. Ensure the `sample_pdfs` folder with the 12 PDF files is present in the project directory.
3. Open `Main Process.xaml` in UiPath Studio.
4. Place or update your ZIP and CSV test files as required.
5. Run the workflow to process the files, compare PDFs, generate the report, and send summary email.

## Requirements

- UiPath Studio (Community or Enterprise)
- Windows OS
- Valid email configuration for sending the summary
- Example/sample CSV and ZIP files as workflow inputs

## Done Using UiPath Studio Activities

Assign, Move File, Unzip File, Read CSV, For Each, Compare Files, Write Range, Send outlook Mail Message

---

*This repository is intended for learning, demo, or template purposes and includes sample files for testing and validation.*

