# Assignment 1 - Transliteration Accuracy Testing

## IT3040 – ITPM | BSc (Hons) in Information Technology | Year 3

## Overview
This project tests the accuracy of the Chat Sinhala transliteration function 
at https://www.pixelssuite.com/chat-translator using Playwright automation.

## Prerequisites
- Python 3.11 or 3.12
- Google Chrome browser

## Installation

1. Clone this repository:
git clone <your-repo-url>

2. Navigate to the project folder:
cd assignment1-test-automation

3. Install dependencies:
pip install playwright openpyxl
playwright install

## How to Run Tests

Run the following command from the project folder:

python test_automation.py --excel "Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open

## Results
- Test results are automatically saved to the Excel file
- The "Actual output" and "Status" columns are filled automatically
- "Pass" means the translation matched the expected output
- "Fail" means the translation did not match the expected output
