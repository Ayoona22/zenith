# Savify: Gamified Savings Platform

**Savify** is a web application designed to help users achieve their financial goals by converting everyday expenses into saving opportunities. It features a personalized dashboard, a task management system, and an AI-powered task generator to help users stay on track with their savings.

---

## Features

- **Financial Dashboard:** Track your total balance, income, and expenses in a personalized view.
- **Task Management:** Create and manage tasks that contribute to your savings.
- **AI-Powered Task Generation:** Uses the **Google Gemini API** to suggest short, actionable tasks based on your saving goals and daily habits.
- **Gamification:** Earn points for task completion and see your rank on a leaderboard.
- **Target Tracking:** Set financial goals and monitor your progress over time.

---

## Technical Stack

| Layer     | Technology                    |
|-----------|-------------------------------|
| Backend   | Python, Flask                 |
| AI        | Google Gemini (`google-generativeai`) |
| Frontend  | HTML, CSS                     |

---

## Getting Started

### Prerequisites

- Python 3.x installed on your machine
- A valid **Google Gemini API Key**

---

### Setup Instructions

1. **Clone the repository**

```bash
git clone https://github.com/ayoona22/zenith.git
cd zenith
```

2. **Create a virtual environment (optional but recommended)**

```bash
python -m venv venv
source venv/bin/activate  # For Windows: venv\\Scripts\\activate
```

3. **Install dependencies**

```bash
pip install -r requirements.txt
```

> Note: If `requirements.txt` is missing, make sure to install:
> - `Flask`
> - `google-generativeai`

4. **Configure the API Key**

- Open `savifyapp.py`
- Replace the placeholder key `AIzaSyCOhPD4G30f8z-IIctTap6zSKIHyv-nsm4` with your actual **Google Gemini API Key**

5. **Run the application**

```bash
python savifyapp.py
```

6. **Access the Application**

Open your browser and go to:

```
http://127.0.0.1:5000
```

---

## Authors

ANNA YACOB
AYOONA MARIA JOHN
DONA BABU

