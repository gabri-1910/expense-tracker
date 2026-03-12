# ExpenseTracker: Small Business Edition 💸

**ExpenseTracker** is a web-based financial management application designed to help small companies move away from messy spreadsheets and gain real-time visibility into their spending. Built with **Python** and **Django**, it provides a secure, scalable, and intuitive platform for tracking business outflows.

## 🚀 The Problem

Small businesses often struggle with "leaky buckets"—minor, untracked expenses that aggregate into significant losses. Traditional accounting software can be overly complex and expensive, while manual ledgers are prone to human error and data loss.

## ✨ Key Features

* **Centralized Dashboard:** A high-level overview of total spending, filtered by week, month, or category.
* **Expense Categorization:** Tag expenses (e.g., Office Supplies, Travel, Utilities) for better tax preparation and budget analysis.
* **Multi-User Support:** Secure login for different team members to submit expenses.
* **Digital Receipt Logging:** Attach digital proof to every transaction to simplify auditing.
* **Exportable Reports:** Generate CSV or PDF summaries for easy sharing with accountants.

## 🛠️ Tech Stack

* **Backend:** Python 3.x
* **Web Framework:** [Django](https://www.djangoproject.com/)
* **Database:** SQLite (Development) / PostgreSQL (Production ready)
* **Frontend:** Django Templates & Bootstrap 5

## ⚙️ Installation & Setup

1. **Clone the Repository:**
```bash
git clone [https://github.com/yourusername/expense-tracker.git](https://github.com/gabri-1910/expense-tracker.git)
cd expense-tracker

```


2. **Create a Virtual Environment:**
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

```


3. **Install Dependencies:**
```bash
pip install -r requirements.txt

```


4. **Run Migrations:**
```bash
python manage.py migrate

```


5. **Create an Admin User:**
```bash
python manage.py createsuperuser

```


6. **Start the Server:**
```bash
python manage.py runserver

```


*The app will be available at `http://127.0.0.1:8000`.*

## 🔒 Security Features

This project leverages Django’s robust security middleware, including:

* **CSRF Protection:** Prevents cross-site request forgery.
* **SQL Injection Protection:** Built-in ORM ensures database queries are sanitized.
* **XSS Protection:** Automatic escaping of variables in templates.
