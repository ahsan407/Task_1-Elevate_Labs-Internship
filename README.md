# 🩺 Task 1: Data Cleaning and Preprocessing – Medical Appointment No Shows

## 📄 Dataset Used:
**Medical Appointment No Shows** – A dataset from Kaggle containing medical appointments and no-show information from Brazil.

---

## 🧹 Data Cleaning Performed (Using Excel):

### 1. ✅ Checked for Missing Values
- Used Excel filters to identify any blank or missing cells.
- No missing (null) values were found.

### 2. ✅ Removed Duplicate Records
- Used Excel’s “Remove Duplicates” feature.
- Duplicate rows found and deleted.

### 3. ✅ Standardized Gender Column
- Used Find and Replace to convert:
  - `"m"` → `"Male"`
  - `"f"` → `"Female"`

### 4. ✅ Fixed Column Name Formatting
- Renamed all columns:
  - Used lowercase letters
  - Replaced spaces with underscores (e.g., `PatientId` → `patient_id`)
  - Corrected spelling errors

### 5. ✅ Fixed Date Format
- Converted date columns to a consistent format: `dd-mm-yyyy` using Excel formulas.

### 6. ✅ Fixed Data Types
- Ensured:
  - `age`, `patient_id`, and `appointment_id` were in **number** format (no scientific notation).
  - Date columns were in proper **date** format.

### 7. ✅ Sorted the Dataset
- Sorted data by the `appointment_date` column in ascending order.

---

## 🛠 Tools Used:
- Microsoft Excel

---

## 📁 Repository Contents:

- `Raw Dataset/`
  - `Medical Appointment No Shows_Raw.xlsx` – Original dataset from Kaggle

- `Cleaned Dataset/`
  - `Medical Appointment No Shows_Cleaned.xlsx` – Final cleaned file after processing

- `LICENSE` – License file for this repository

- `README.md` – This documentation file

---

## ✅ Outcome:
- A clean and well-structured dataset ready for analysis or modeling.
- All inconsistencies, nulls, duplicates, formatting issues, and data types were addressed using Excel.

---

## 📌 Task Submission
Submitted as part of the **Elevate Labs Internship – Task 1: Data Cleaning & Preprocessing**.
