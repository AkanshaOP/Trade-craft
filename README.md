# Trade Craft App 🎯


A simplified financial trading application built to demonstrate **full-stack development** skills:
- Secure APIs
- Frontend–backend integration
- Authentication & KYC
- Product listing & details
- Transactions & portfolio dashboard
- Watchlist functionality  

---

## 🚀 Features

### 🔐 Authentication & KYC
- User registration & login with JWT authentication  
- KYC form: Name, Email, PAN, Dummy ID upload  
- Wallet initialized with ₹100,000 on signup  

### 📊 Products
- Seeded list of dummy investment products (stocks/mutual funds)  
- Each product has: name, category, price per unit, P/E ratio, and history data  
- Product detail page shows extended info + chart  

### 💸 Transactions & Portfolio
- Users can **buy products** (units deducted from wallet)  
- Transactions stored in DB  
- Portfolio dashboard shows:  
  - Total invested  
  - Current value (units × latest price)  
  - Returns (current − invested)  

### ⭐ Watchlist
- Add/remove products to personal watchlist  

---

## 🧩 Tech Stack
- **Frontend:** React, React Router, Chart.js / Recharts, Axios  
- **Backend:** Node.js, Express, JWT, Multer  
- **Database:** MongoDB  
- **Styling:** Tailwind / CSS  

---

## 📁 Project Structure
