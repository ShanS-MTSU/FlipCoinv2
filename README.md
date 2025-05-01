README.txt
-----------
FlipCoin Cryptocurrency Project
Author: Shan Sindy
Date: 05/01/2025

This project is a full-stack cryptocurrency trading simulation named FlipCoin.
It includes:

1. Django-based backend (CryptoBackend)
2. Vue.js-based frontend (flipcoin-frontend)
3. Live cryptocurrency data via CoinGecko API
4. JWT-based secure user authentication

============================
1. HOW TO RUN THE BACKEND (CryptoBackend - Django)
============================

REQUIREMENTS:
- Python 3.x
- pip
- virtualenv
- MySQL or SQLite
- Django and dependencies (from requirements.txt)

STEPS:
1. Open a terminal and navigate to the backend folder:
   cd CryptoBackend

2. Create and activate a virtual environment:
   python3 -m venv venv
   source venv/bin/activate

3. Install the required packages:
   pip install -r requirements.txt

4. Run migrations to set up the database:
   python manage.py migrate

5. (Optional) Create a superuser:
   python manage.py createsuperuser

6. Start the backend server:
   python manage.py runserver

Access backend at: http://127.0.0.1:8000/

============================
2. HOW TO RUN THE FRONTEND (flipcoin-frontend - Vue.js)
============================

REQUIREMENTS:
- Node.js and npm
- Vue CLI installed (install with: npm install -g @vue/cli)

STEPS:
1. Open a new terminal window.
2. Navigate to the frontend folder:
   cd flipcoin-frontend

3. Install dependencies:
   npm install

4. Start the Vue development server:
   npm run serve

Access frontend at: http://localhost:8080/

============================
3. NOTES
============================
- Make sure the backend server is running before you start the frontend.
- The frontend will fetch live cryptocurrency prices from the CoinGecko API.
- Prices auto-refresh every 30 seconds.
- User authentication is handled securely using JSON Web Tokens (JWT).
- Project simulates a functional crypto wallet and transaction system.

