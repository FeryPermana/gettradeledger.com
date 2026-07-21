# 📈 TradeLedger

> Modern Investment & Trading Portfolio Management Platform built with Laravel and Vue.js.

TradeLedger is a full-stack web application designed to help investors and traders manage their portfolios, monitor performance, record trades, analyze investments, and build long-term wealth with comprehensive financial insights.

---

## ✨ Features

### 🔐 Authentication
- User Registration & Login
- Email Verification
- Password Reset
- Laravel Sanctum Authentication

### 💼 Portfolio Management
- Create Manual Portfolio
- Trade Synced Portfolio
- Portfolio Allocation
- Portfolio Summary
- Unrealized Profit & Loss
- Multi Account Support
- Multi Currency Support

### 📊 Trading Journal
- Trade History
- Win Rate Analysis
- Risk Reward Analysis
- Trade Performance
- Position Tracking
- Partial Close

### 💰 Investment Analytics
- Portfolio Value
- Current Market Value
- Average Cost
- Total Investment
- Gain / Loss
- Asset Allocation
- Category Allocation

### 💱 Currency Converter
- Multi Currency Portfolio
- Automatic Currency Conversion
- Base Currency Support

### 📈 Price Management
- Manual Price Update
- Automatic Price Sync (Premium)
- Last Price Update Tracking

### 👑 Premium Membership
- Manual Payment Verification
- Multiple Subscription Plans
- Premium Expiration
- Payment Management
- Admin Approval System

### 🛡 Security
- Authentication
- Authorization
- Request Validation
- API Resource Protection
- Transaction Handling
- Database Integrity

---

# 🛠 Tech Stack

## Backend

- PHP 8.x
- Laravel 12
- MySQL
- Laravel Sanctum
- PHPUnit
- Docker

## Frontend

- Vue.js 3
- Vue Router
- Pinia
- Tailwind CSS
- Axios
- Vite

## DevOps

- Docker
- Docker Compose
- Nginx
- GitHub Actions *(planned)*

---

# 📂 Project Structure

```
gettradeledger.com
│
├── backend
│   ├── app
│   ├── routes
│   ├── database
│   ├── tests
│   └── ...
│
├── frontend
│   ├── src
│   ├── public
│   └── ...
│
├── docker-compose.yml
└── README.md
```

---

# 🚀 Getting Started

## Clone Repository

```bash
git clone https://github.com/yourusername/gettradeledger.com.git

cd gettradeledger.com
```

---

## Run with Docker

```bash
docker compose up -d --build
```

Backend

```
http://localhost:8000
```

Frontend

```
http://localhost:5173
```

MySQL

```
localhost:3307
```

---

## Backend Setup

```bash
cd backend

cp .env.example .env

composer install

php artisan key:generate

php artisan migrate

php artisan storage:link
```

---

## Frontend Setup

```bash
cd frontend

npm install

npm run dev
```

---

# 🧪 Running Tests

Backend

```bash
php artisan test
```

or

```bash
php artisan test --parallel
```

---

# 📦 API

TradeLedger provides RESTful APIs for:

- Authentication
- Portfolio
- Assets
- Accounts
- Trades
- Analytics
- Payment
- Premium Membership
- Currency Conversion

---

# 📌 Roadmap

- [x] Authentication
- [x] Portfolio Management
- [x] Trading Journal
- [x] Analytics Dashboard
- [x] Multi Currency
- [x] Premium Membership
- [x] Docker Support
- [ ] Dividend Module
- [ ] Watchlist
- [ ] Stock Screener
- [ ] Notification System
- [ ] Automatic Price Sync
- [ ] Dividend Calendar
- [ ] Portfolio Rebalancing
- [ ] Mobile Application

---

# 🤝 Contributing

Contributions, issues, and feature requests are welcome.

Please create a feature branch before submitting a pull request.

```
feature/new-feature
```

---

# 📄 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

**Muhammad Pandi Ferry Permana**

Software Engineer | Backend Developer | Investment Enthusiast

---

## 🌐 Vision

TradeLedger aims to become an all-in-one Investment Operating System for modern investors by combining portfolio management, trading journal, investment analytics, dividend tracking, and wealth-building tools into a single platform.