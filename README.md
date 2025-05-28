# -ecommerce-checkout
# 🛒 eCommerce Checkout Flow Simulation

This is a mini eCommerce application built to simulate a real-world product purchase flow. It covers everything from selecting a product to checkout, handling transactions, and confirming orders.

## 🚀 Live Demo

Check out the live working version here:  
👉 [https://ecommerce-checkout-swart.vercel.app](https://ecommerce-checkout-swart.vercel.app)

---

## 📌 Features

### 1. Landing Page
- Product image, title, description, and price
- Variant (e.g., size, color) and quantity selector
- “Buy Now” button to go to checkout

### 2. Checkout Page
- User input form with validation (name, email, phone, address, card info)
- Real-time order summary showing selected product details
- Transaction simulation with 3 scenarios:
  - ✅ Approved
  - ❌ Declined
  - ⚠️ Gateway Failure

### 3. Thank You Page
- Displays order summary, customer input, and unique order ID
- Confirmation email sent using Mailtrap (sandbox)

---

## 🧰 Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js + Express
- **Database**: MongoDB
- **Email Service**: Mailtrap.io

---

## ⚙️ Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/Shaikh-007-eng/ecommerce-checkout.git
cd ecommerce-checkout
