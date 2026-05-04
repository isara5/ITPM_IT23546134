# IT3040 – ITPM Semester 1 - Assignment 1
## Option 1: Transliteration Accuracy Testing

### Student Details
- Name: JAYARATHNA J I N
- Registration Number: IT23546134
- Batch: Year 3 - Semester 1

---

### Project Overview
The main objective of this assignment is to evaluate the correctness of the "Chat Sinhala" transliteration function provided by [PixelsSuite Chat Translator](https://www.pixelssuite.com/chat-translator). This project identifies 50 specific scenarios where the system fails to correctly convert chat-style Singlish into Sinhala, covering all 24 input types specified in the assignment guidelines.

### Technologies Used
- Language: Python 3.11/3.12
- Automation Framework: Playwright
- Data Handling: Openpyxl (Excel)

---

### Prerequisites
Before running the script, ensure you have the following installed:
1. Python 3.11+
2. Google Chrome Browser

### Installation & Setup

1. Navigate to the project directory:
   Open Command Prompt/Terminal and go to your extracted folder:
   ```cmd
   cd IT23546134

### Install required Python dependencies:

python -m pip install playwright openpyxl

### Install Playwright Browser binaries:

python -m playwright install chromium

### How to Run the Automation Script
1. Make sure the Excel file IT23546134_Assignment 1 - Test cases.xlsx is closed.
2. Run the following command in your terminal:

python IT23546134_test_automation.py --excel "IT23546134_Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open


### Folder Structure & Included Files
1. IT23546134_test_automation.py - The automation script designed to test the 50 identified scenarios.
2. IT23546134_Assignment 1 - Test cases.xlsx - Completed Excel sheet with 50 failure test cases, actual results, status (FAIL), and rationales.
3. Git Link - IT23546134.txt - Contains the link to the public Git repository.
4. README.md - Documentation of the project setup and execution.

### Testing Summary
1. Total Test Cases: 50
2. Pass Status: 0
3. Fail Status: 50 (All test cases are identified system failures)