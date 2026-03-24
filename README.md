# 💸 Smart Expense Tracker (ML Powered)

Automatically detects transactions from SMS, classifies them using Machine Learning, and shows real-time spending insights.

---

## 🚀 What It Does

* 📩 Reads transaction SMS
* 🧠 Classifies expenses (Food, Travel, Shopping, etc.)
* 📊 Shows spending insights
* 🔔 Helps track and control expenses

---

## 🧩 Architecture

```
SMS → Android App → Flask API → ML Model → Database → Dashboard
```

---

## 🛠️ Tech Stack

* 📱 Android (Java)
* 🌐 Flask (Python)
* 🧠 Scikit-learn (ML + NLP)
* 💾 SQLite / Firebase

---

## 📂 Project Structure

```
smart-expense-tracker/
│
├── android-app/        # 📱 Mobile app (SMS reader + UI)
├── backend/            # 🌐 Flask API (handles requests)
│   ├── app.py
│   ├── model.py
│   ├── utils.py
│   └── requirements.txt
│
├── ml-model/           # 🧠 ML training & dataset
│   ├── train.py
│   └── dataset.csv
│
├── docs/               # 📄 Screenshots, demo assets
│
├── README.md
└── .gitignore
```

---

## ⚙️ Run Locally

```bash
git clone https://github.com/yourusername/smart-expense-tracker.git
cd smart-expense-tracker/backend
pip install -r requirements.txt
python app.py
```

---

## 🧪 Example

**Input:** `"₹250 spent at Zomato"`
**Output:** `Food`

---

## 🔥 Future Work

* Bank API integration
* Budget alerts
* Spending prediction

---

## 👨‍💻 Author

Ami Krishna
