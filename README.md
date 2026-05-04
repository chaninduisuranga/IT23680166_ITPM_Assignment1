# Singlish Transliteration Accuracy Testing

## Prerequisites
- Python 3.11 or 3.12
- Playwright
- Openpyxl (for Excel handling)

## Installation
1. Install the required Python packages:
   pip install playwright openpyxl
2. Install the Playwright browser drivers:
   playwright install chromium

## How to run tests
Run the following command in your terminal 

python test_automation.py --excel "Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 100 --slow-mo-ms 300 --save-every 1 --keep-open

## Notes
- Ensure the Excel file is closed before running the script.
- The results (Actual output and Status) will be automatically updated in the Excel file.