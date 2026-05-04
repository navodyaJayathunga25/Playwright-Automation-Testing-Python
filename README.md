# Singlish to Sinhala Transliteration Testing

Automated test suite for evaluating the accuracy of Chat Sinhala transliteration at [pixelssuite.com/chat-translator](https://www.pixelssuite.com/chat-translator) using Python and Playwright.

## Prerequisites

- Python 3.11 or 3.12
- Google Chrome (recommended)

## Installation

1. Clone the repository:
```bash
   git clone https://github.com/your-username/your-repo-name.git](https://github.com/navodyaJayathunga25/Playwright-Automation-Testing-Python.git
   cd Playwright-Automation-Testing-Python
```

2. Install dependencies:
```bash
   pip install -U pip
   pip install playwright openpyxl
   playwright install
```

## Running the Tests

```bash
python test_automation/test_automation.py --excel "test_automation/Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open
```

After execution, open the Excel file to verify the **Actual output** and **Status** columns are populated.

## Project Structure

```
├── test_automation/
│   ├── test_automation.py
│   ├── Assignment 1 - Test cases.xlsx
│   └── Commands.txt
├── .gitignore
└── README.md
```

## Test Coverage

50 negative test cases covering all 24 Singlish input types including question forms, command forms, greetings, slang, emojis, English word insertions, numbers, dates, URLs, and more.
