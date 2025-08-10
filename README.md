# 💼 FinSage – AI-Powered Personal Finance Assistant

## 📌 Overview
**FinSage** is an intelligent, full-stack personal finance manager developed with **Django**.  
It allows you to **log income and expenses**, **analyze financial behavior**, and **receive tailored advice** for budgeting, saving, and investing.

With the integration of **cutting-edge AI models**, FinSage delivers **practical insights** and **custom monthly budget suggestions**, making financial management **clear, data-driven, and stress-free**.

---

## ✨ Main Features
- 🔐 **Secure User Accounts** – Register, log in, and log out with session-based security.  
- 💰 **Transaction Management** – Record, update, delete, and categorize income/expenses with notes and dates.  
- 📊 **Interactive Dashboard** – Visual charts for income trends, spending habits, and category analysis.  
- 🤖 **Smart AI Advisor**  
  - Evaluates your financial status.  
  - Suggests monthly budgets tailored to your spending.  
  - Recommends savings and investment opportunities.  
  - Provides clean, plain-text explanations.  
- 🧾 **Bill Scanning & OCR** – Upload bills/receipts and let AI + OCR extract details automatically.  
- 📂 **Data Export** – Save transaction history as CSV.  
- 📑 **PDF Reports** – Generate summaries with tables, charts, and totals in PDF format.  
- 🎯 **Advanced Filters** – Search by amount, category, date range, or keywords.  
- 📱 **Responsive Design** – Optimized for desktop and mobile using Bootstrap 5 + Chart.js.  

---

## 🛠 Tech Stack

| Layer        | Tools |
|--------------|-------|
| **Backend**  | Django, Django ORM |
| **Frontend** | Bootstrap 5, Chart.js, Animate.css |
| **AI**       | Groq API (LLM for finance and OCR parsing) |
| **OCR**      | Tesseract (pytesseract) |
| **Database** | SQLite (default) |
| **Other**    | HTML5, CSS3, JavaScript |

---

## 🚀 Setup Guide

### **Requirements**
Before starting, make sure you have:
- Python 3.8+  
- Django 4.x+  
- Groq API key  
- Installed Tesseract OCR  

⚠ **Note:** Tesseract is **not bundled** with this repo.  
Download it from [Tesseract OCR GitHub](https://github.com/tesseract-ocr/tesseract) or your OS package manager.  
Set its location in `.env` after installation.

---

### **Installation Steps**

#### 1️⃣ Clone this repo
```bash
git clone https://github.com/RoopikaBiju/personal-finance-assistance.git
cd personal-finance-assistance
```

#### 2️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

#### 3️⃣ Set up environment variables

Create a `.env` file in the project root:

```ini
GROQ_API_KEY=your_groq_api_key
TESSERACT_CMD=path_to_tesseract_executable
```

Example (Windows):

```ini
TESSERACT_CMD=C:\Program Files\Tesseract-OCR\tesseract.exe
```

#### 4️⃣ Apply database migrations

```bash
python manage.py migrate
```

#### 5️⃣ Run the development server

```bash
python manage.py runserver
```

---

## 📖 Usage Guide

1. **Sign up or log in.**
2. **Add income & expenses** with categories and descriptions.
3. **Upload bills/receipts** — FinSage auto-extracts details via OCR.
4. **View dashboard** — Analyze your spending and income trends.
5. **Ask the AI assistant** for personalized budgets & investment tips.
6. **Export your data** as CSV or PDF reports.

---
---

## 🎨 Customization

* **AI Models**: Modify Groq API model settings for different insights.
* **Categories**: Add/edit transaction categories via Django Admin.
* **UI Styling**: Customize Bootstrap theme & Chart.js visuals in `/static`.

---

## 🤝 Contributing

Contributions are welcome!

* Fork the repository
* Create a feature branch
* Submit a pull request

For major changes, open an issue to discuss your ideas before implementation.

---

## 👥 Contributors
This project was developed by:
- **Roopika Biju** – [GitHub Profile](https://github.com/RoopikaBiju)
- **Robby R Thomas 1** – [GitHub Profile](https://github.com/robby-516)
- **Jayasankar K S** – [GitHub Profile](https://github.com/jayasankarks3378)

---

## 📜 Usage Terms
This project is shared for educational and demonstration purposes only.  
You may view and run the code locally, but you may not modify, redistribute, or use it for commercial purposes without explicit permission from the author.

---

**FinSage – Empower your financial decisions with AI. 🚀**



