# Singlish to Sinhala Chat-Translator Test Automation

This repository contains a comprehensive test automation suite designed for a Singlish to Sinhala Chat-Translator. The primary objective is to evaluate the linguistic accuracy and technical reliability of the translation engine when processing informal, phonetic, and code-mixed Singlish inputs. By utilizing automated testing scripts, this project ensures that colloquial expressions and digital short-hands are correctly mapped to their native Sinhala equivalents.

## Features
- Automates 50+ test cases (Negative).
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
