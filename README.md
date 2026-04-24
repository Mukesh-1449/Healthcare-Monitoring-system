# 🏥 Healthcare Monitoring System (C Language)

## 📌 Overview

The Healthcare Monitoring System is a menu-driven C program designed to manage patient health records. It allows users to add, view, search, update, and analyze patient health data such as temperature, heart rate, and blood pressure.

---

## 🚀 Features

* ➕ Add new patient details
* 📋 Display all patient records
* 🔍 Search patient by ID
* ✏️ Update patient health data
* ❤️ Check basic health status
* ❌ Exit system

---

## 🛠️ Technologies Used

* C Programming Language
* Standard Libraries:

  * stdio.h
  * string.h

---

## 📂 Project Structure

Healthcare-Monitoring-System/
│
├── main.c          # Main source code
└── README.md       # Project documentation

---

## ⚙️ How It Works

The program uses:

* Structures (`struct`) to store patient data
* Arrays to manage multiple patients
* Functions for modular operations
* Menu-driven interface for user interaction

---

## 🧾 Patient Data Stored

Each patient record includes:

* ID
* Name
* Age
* Temperature (°C)
* Heart Rate (bpm)
* Blood Pressure (Systolic/Diastolic)

---

## ▶️ How to Run

### Step 1: Compile the Program

gcc main.c -o healthcare

### Step 2: Run the Program

./healthcare

---

## 📊 Sample Menu

--- Healthcare Monitoring System ---

1. Add Patient
2. Display Patients
3. Search Patient
4. Update Patient Data
5. Check Health Status
6. Exit

---

## ❤️ Health Status Logic

The system checks:

* Temperature > 37.5°C → Fever
* Heart Rate < 60 or > 100 → Abnormal
* Blood Pressure > 140/90 → High Blood Pressure

---

## 🔒 Limitations

* Maximum 100 patients
* Data is not saved permanently (no file storage)
* Basic validation only

---

## 🔮 Future Improvements

* File handling for permanent storage
* GUI interface
* Mobile or web version
* Login authentication system

---

## 👨‍💻 Author

Mukesh

---

## 📄 License

This project is open-source and free to use for educational purposes.
