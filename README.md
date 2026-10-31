# 💰 BudgetNest – Family Budget and Expense Tracker

**BudgetNest** is a Django-based web application designed to help individuals and families manage their daily expenses, organize family members, and monitor their spending habits.

The application provides an organized platform to record expenses, manage family details, and view monthly and yearly expense reports.

## 🚀 Features

- **Expense Management:** Add, view, and update daily expenses.
- **Family Management:** Add and manage family members.
- **Expense Tracking:** Monitor family and individual spending.
- **Dashboard:** View expense summaries and financial information.
- **Monthly Reports:** Analyze expenses month by month.
- **Yearly Reports:** Review annual spending patterns.
- **User Accounts:** Organize user-related functionality.
- **Responsive Interface:** Simple web interface using HTML and CSS.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Backend programming |
| Django | Web application framework |
| SQLite | Database management |
| HTML5 | Frontend structure |
| CSS3 | Styling and design |
| JavaScript | Client-side functionality |
| PyCharm | Development environment |
| Git & GitHub | Version control |

## 📂 Project Structure

```text
BudgetNest/
│
├── accounts/
│   ├── migrations/
│   ├── templates/
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   └── views.py
│
├── family/
│   ├── migrations/
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   └── views.py
│
├── BudgetNest/
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
│
├── static/
│   ├── css/
│   └── images/
│
├── templates/
│   ├── base.html
│   ├── navbar.html
│   ├── dashboard.html
│   ├── add_expense.html
│   ├── view_expense.html
│   ├── add_family.html
│   ├── update_expense.html
│   ├── monthly_report.html
│   └── yearly_report.html
│
├── manage.py
├── .gitignore
└── README.md
```

## ⚙️ Installation and Setup

Follow these steps to run BudgetNest locally.

### 1. Clone the repository

```bash
git clone https://github.com/Vedasree-Kummaragunta/BudgetNest.git
```

### 2. Navigate to the project directory

```bash
cd BudgetNest
```

### 3. Create a virtual environment

```bash
python -m venv venv
```

### 4. Activate the virtual environment

**Windows:**

```bash
venv\Scripts\activate
```

### 5. Apply database migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### 6. Start the development server

```bash
python manage.py runserver
```

### 7. Open the application

Visit the following URL in your browser:

```text
http://127.0.0.1:8000/
```

## 🗄️ Database

BudgetNest uses SQLite as its database.

Django ORM is used to interact with the database and manage application data.

## 🔐 Security

- Sensitive configuration values should be stored in environment variables.
- The Django secret key should not be committed to GitHub.
- The `.env` file and local database should be excluded using `.gitignore`.

## 🔮 Future Enhancements

- Interactive expense analytics and charts.
- Budget limit setting and alerts.
- Export expense reports to PDF and Excel.
- Advanced spending analysis.
- Cloud database integration.
- Improved mobile-friendly interface.
