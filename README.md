# 💸 Expense Tracker Lite

A simple and intuitive web application to track daily expenses, built using **Flask**, **SQLite**, and **Tailwind CSS**.

---

## 🚀 Features

* ➕ Add, edit, and delete expenses
* 📅 Filter expenses by date range
* 🏷️ Filter by category
* 📊 Visualize spending with charts (Pie & Bar)
* 💾 Export filtered data as CSV
* 💡 Clean and responsive UI using Tailwind CSS

---

## 🛠️ Tech Stack

* **Backend:** Flask (Python) 
* **Database:** SQLite (via SQLAlchemy ORM) 
* **Frontend:** HTML, Tailwind CSS 
* **Charts:** Chart.js 

---

## 📂 Project Structure

```
expense-tracker/
│── app.py
│── instance/
│   └── expenses.db
│── templates/
│   ├── base.html
│   ├── index.html
│   └── edit.html
```

---

## ⚙️ Installation & Setup

1. Clone the repository:

```bash
git clone https://github.com/PK-KN/Expense-Tracker.git
cd expense-tracker
```

2. Create and activate a virtual environment (recommended):

```bash
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
```

3. Install dependencies:

```bash
pip install flask flask_sqlalchemy
```

4. Run the application:

```bash
python app.py
```

5. Open your browser and go to:

```
http://127.0.0.1:5000/
```

---

## 📊 How It Works

* Expenses are stored in a local SQLite database.
* Users can:

  * Add new expenses with category and date
  * Edit or delete existing entries
  * Apply filters (date range & category)
* Charts dynamically update based on filtered data.
* CSV export allows downloading expense reports.

---

## 📌 Categories

Default categories include:

* Food
* Transport
* Rent
* Utilities
* Health

---

## 🧠 Future Improvements

* User authentication (login/signup)
* Monthly budget tracking
* Recurring expenses
* Cloud deployment (Render / Railway)

---

## 📄 License

This project is open-source and free to use.

---

## 👤 Author

Palivela Karthik Narendra

GitHub: https://github.com/PK-KN

---
