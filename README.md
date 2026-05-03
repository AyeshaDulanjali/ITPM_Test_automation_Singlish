# Singlish to Sinhala Chat-Translator Test Automation

This project automates the testing of a Singlish-to-Sinhala chat translator tool using **Playwright** and **Python**. It performs automated input entry from an Excel sheet and captures the actual output and pass/fail status.

## Features
- Automates 50+ test cases (Positive and Negative).
- Captures screenshots for failed test cases.
- Generates a detailed HTML test report.
- Saves results directly to an Excel workbook.

## Setup Instructions
1. Clone the repository.
2. Create a virtual environment: `python -m venv .venv`
3. Activate the environment: `.venv\Scripts\activate`
4. Install dependencies: `pip install playwright openpyxl pandas`
5. Run the automation:
   ```bash
   python test_automation.py --excel "Assignment 1 - Test cases - New_5.xlsx" --url "YOUR_TEST_URL"
