# 🧾 Retail Billing App

This is my **first project** built as part of my **BTech First Training**. It's a GUI-based Retail Billing Software using Python (Tkinter), allowing users to:

- Add items (Juices, Chips, Chocolates)
- Automatically calculate total + tax
- Generate and save bill
- Send bill PDF via email
- Store transaction in a CSV
- Search old bills

---

## 📸 GUI Preview

> A simple Tkinter-based interface for real-time billing and record management.

---

## 🔧 Features

- ✅ Total Bill & Tax Calculation
- ✅ PDF Generation using `reportlab`
- ✅ Send bill via Email (`smtplib`)
- ✅ Save data to `.txt` and `.csv`
- ✅ Bill Search from saved files
- ✅ Auto-scroll welcome text

---

## 🧠 Technologies Used

- Python 3.x
- Tkinter (GUI)
- ReportLab (PDF generation)
- smtplib (Email sending)
- dotenv (For hiding credentials)
- pandas (CSV handling)

---

## 🔒 Security

Sensitive data like **Gmail** and **App Password** are stored securely in a `.env` file, and `.gitignore` is used to avoid pushing them to GitHub.

EMAIL=your_email@gmail.com
APP_PASSWORD=your_app_password

## ⚙️ How to Run

### 🛠️ 1. Install Requirements

```bash
pip install -r requirements.txt

run the app----
python main.py

