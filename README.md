
# IT3040 Assignment 1 – Singlish Transliteration Testing (Playwright Automation)

## 📌 Project Overview

This repository contains the **automation script and test cases** for **IT3040 – IT Project Management (Year 3, Semester 1)**.

The project evaluates the accuracy of a **Singlish-to-Sinhala transliteration system** by executing automated test cases and identifying conversion failures.

🔗 Tested System:
[https://www.pixelssuite.com/chat-translator](https://www.pixelssuite.com/chat-translator)

---

## 🎯 Objectives

* Evaluate **Singlish → Sinhala transliteration accuracy**
* Identify incorrect or failed conversions
* Automate testing using **Playwright (Python)**
* Store results in an **Excel file**
* Analyze UI behavior and output updates

---

## 🛠 Technologies Used

* **Python**
* **Playwright**
* **OpenPyXL**

---

## 📂 Project Structure

```
IT23367326/
│
├── IT23367326.py
├── IT23367326_Assignment1_TestCases.xlsx
├── IT23367326_GitRepoLink.txt
├── IT23367326_requirements.txt
├── README.md
```
---

## ⚙️ Prerequisites

Make sure you have:

* Python **3.8 or above**
* pip installed
* Internet connection

---

## 📥 Installation Steps

### 1. Open project folder

Extract the ZIP file and open the folder in terminal

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Install Playwright browser

```bash
playwright install chromium
```

---

## ▶️ Run the Automation Script

```bash
python test_automation.py --excel "IT23367326_Assignment1_TestCases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1
```
---

## 📊 Output

* Results are written directly into the Excel file:

  * **Actual Output**
  * **Status (PASS / FAIL / UI Error / COLLECTED)**

---

## 🧪 Test Coverage

### ✔ Functional Testing

* Question forms
* Commands and responses
* Greetings
* Mixed Singlish + English
* Numbers, dates, currency
* Emojis and symbols

### ✔ Negative Testing

* Spacing errors
* Typo inputs
* Slang language
* Mixed formats

### ✔ UI Testing

* Real-time Sinhala output updates

---

## ⚠️ Important Notes

* Strict comparison is used → small differences = FAIL
* Some failures are expected due to:

  * Transliteration limitations
  * Informal Singlish variations
  * UI timing delays

---

## ❗ Troubleshooting

### Install issues

```bash
pip install -r requirements.txt --force-reinstall
```

### Playwright issues

```bash
playwright install --force chromium
```

### Common problems

* No output → increase `--wait-ms`
* UI not updating → increase `--slow-mo-ms`

---

## 📦 Submission Instructions (IMPORTANT)

1. Rename all files using your student ID:

   * IT23367326_Assignment1_TestCases.xlsx
   * IT23367326_GitRepoLink.txt

2. Create a folder:

```
IT23367326/
```

3. Add all files into the folder

4. Zip the folder:

```
IT23367326.zip
```

5. Upload the ZIP file to CourseWeb

---

## 👨‍🎓 Student Information

* Student ID: **IT23367326**
* Module: **IT3040 – IT Project Management**
* Assignment: **Assignment 1 (Option 1)**

---

## 📜 License

Academic use only.

---
