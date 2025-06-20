# Invoice Tracking System

A desktop application built with Python's Tkinter library to upload, validate, and track invoices efficiently.

## 🚀 Features

- Upload invoice PDFs via user-friendly interface
- Validate duplicate entries based on Order ID
- Ensure required fields (Order Date, Invoice Date, etc.) are present
- View a list of submitted invoices with details
- Generate basic Excel reports (optional)

## 🛠 Tech Stack

- **Frontend**: Tkinter (Python GUI library)
- **Backend**: Python
- **File Handling**: `os`, `pdfplumber` / `PyPDF2` (optional for PDF reading)
- **Data Storage**: In-memory or CSV/Excel (optional)
- **Reporting**: `openpyxl` / `pandas` (optional)

## 📸 Screenshots

_Add screenshots here after running the app._

## 📂 Project Structure

invoice-tracking-system/
├── main.py # Main application file
├── utils.py # Utility functions (validation, parsing, etc.)
├── data/ # Folder to store invoices or logs
└── README.md


## ✅ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/invoice-tracking-system.git
   cd invoice-tracking-system
   
2. Install required packages (if any):
   pip install -r requirements.txt
   
3. Run the application:
   python main.py
