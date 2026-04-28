Here’s a clean and professional **README.md** you can use for your project:

---

# 📊 Product Review Analyzer

A fully functional **Product Review Analyzer Web App** with **Admin & User Authentication**, built using **HTML, CSS, and JavaScript (Vanilla JS + LocalStorage)**.

This application allows users to submit, edit, and manage product reviews, while admins have full control over all data.

---

## 🚀 Features

### 👤 User Features

* Register and login
* Add product reviews
* Edit and delete **own reviews only**
* View all reviews
* Reset password (username-based)

### 👑 Admin Features

* Secure admin login
* Delete **any review**
* Change admin password
* Reset admin password using master reset code

### 📊 Analytics Dashboard

* Total reviews count
* Overall average rating
* Sentiment analysis (Excellent / Good / Average / Poor)
* Product-wise breakdown:

  * Number of reviews
  * Average rating
  * Sentiment per product

### 📝 Review Management

* Add reviews with:

  * Product name
  * Rating (1–5 stars)
  * Comment
* Edit reviews via modal
* Sort reviews by:

  * Product name
  * Rating

### 💾 Data Storage

* Uses **LocalStorage**
* No backend required
* Data persists in browser

---

## 🔐 Default Credentials

### Admin Login

```
Password: admin123
```

### Admin Reset

```
Master Reset Code: reset123
```

---

## 🛠️ Tech Stack

* **HTML5**
* **CSS3 (Modern UI with gradients & animations)**
* **JavaScript (ES6)**
* **LocalStorage API**

---

## 📂 Project Structure

```
project/
│
├── index.html   # Main application file (contains HTML, CSS, JS)
└── README.md    # Documentation
```

---

## ▶️ How to Run

1. Download or clone the project
2. Open `index.html` in any browser
3. Start using the app

No installation required 🎉

---

## 🧠 How It Works

* User and review data are stored in:

  * `localStorage.reviewUsers`
  * `localStorage.productReviews`
  * `localStorage.adminCredentials`

* Authentication is handled entirely on the client side

---

## ⚠️ Limitations

* No real backend (not production secure)
* Passwords stored in plain text (for demo purposes only)
* Reset mechanisms are simplified (no email/SMS)

---

## 💡 Future Improvements

* Add backend (Node.js / Firebase)
* Encrypt passwords
* Add search & filters
* Pagination for reviews
* Image uploads for products
* Dark mode 🌙

---

## 📸 UI Highlights

* Clean modern UI
* Responsive layout
* Modal-based interactions
* Animated login screens

---

## 📜 License

This project is for **educational/demo purposes**.
You are free to modify and use it.

---
