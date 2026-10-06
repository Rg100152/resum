# 🛍️ RESUM — Multi-Category E-Commerce & Management Web Portal

![GitHub repo size](https://img.shields.io/github/repo-size/Rg100152/resum?style=for-the-badge&color=4f46e5)
![GitHub stars](https://img.shields.io/github/stars/Rg100152/resum?style=for-the-badge&color=06b6d4)
![GitHub forks](https://img.shields.io/github/forks/Rg100152/resum?style=for-the-badge&color=ec4899)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**RESUM** ek modern, dynamic aur responsive multi-category e-commerce web platform hai. Is web application ko clean vanilla web technologies (HTML5, Modern CSS3, JavaScript) par banaya gaya hai jisme customer shopping experience ke saath-saath complete admin management dashboard, real-time cart calculator, aur instant booking system integrated hai.

---

## 🚀 Key Highlights & Features

- **🎨 Multi-Category Catalog Showcase:**
  - **Fashion & Ethnic Wear:** Designer Sarees (`saari.html`), Bridal Lehengas (`lehnga.html`), Punjabi Patiala & Dhoti Suits (`patiyala.html`), Formal & Casual Shirts (`shirt.html`), aur Tailored Men's Pants (`pant.html`).
  - **Accessories & Opticals:** UV Protection Glasses & Smart Eyewear (`glases.html`) aur Streetwear Caps (`cap.html`).
  - **Stationery & Fine Arts:** Literature & Philosophy Books (`books.html`), Fine Nib Pens (`pen.html`), Professional Color Brushes (`color brush.html`), aur Premium Notebooks (`notbook.html`).
  - **Kids & Entertainment:** Friction Toys & Early Learning Kits (`toy.html`).

- **⚡ Real-Time Interactive Cart System (`cart.html`):**
  - Dynamic quantity increment/decrement (`+` / `-`).
  - Live subtotal, platform discount, shipping calculation aur auto-updating total.
  - Smooth item removal with fade-out animations.

- **📊 Admin Management Dashboard (`dashboard.html`):**
  - Store analytics KPI counters (Revenue, Total Orders, Active Bookings, Low Churn).
  - Recent orders tracking table with colored status badges (`Confirmed`, `Pending`, `Cancelled`).
  - Quick administrative shortcuts for managing catalog pages.

- **📦 Inventory Publishing Hub (`add product.html`):**
  - Two-column layout with a **Real-Time Live Product Card Preview**.
  - Dynamic input mirroring for title, categories, prices, badges, and image URLs.
  - Local file image preview using the browser's `FileReader` API.

- **⚡ Express Order Booking (`book now.html`):**
  - Direct checkout flow for quick delivery without multi-step friction.
  - Interactive payment selector (Cash on Delivery, UPI QR, Debit/ATM Card).
  - Animated modal receipt generating random Order IDs and delivery confirmations.

- **🔍 Instant Catalog Search (`search.html`):**
  - Real-time client-side search filtering by keywords, titles, and categories.
  - Supports URL query parameters (`search.html?q=keyword`).
  - Interactive category chip buttons.

- **🔐 Authentication & User Onboarding:**
  - Classic Login (`login.html`), Quick Sign-In with OTP toggle (`singn in.html`), Simple Registration (`singnup.html`), aur detailed Profile Setup (`creat account.html`).
  - Interactive password visibility toggles (`eye/eye-slash`) aur live password strength meters.

- **👤 Developer Profile & Contact (`contactme.html`):**
  - Integrated profile card featuring developer details, skill badges, social handles, and an interactive query dispatch form.

---
url of my this website is https://resumbooking.netlify.app

## 📂 Project Directory Structure

```text
resum/
├── index.html                  # Main Storefront & Category Navigation Hub
├── dashboard.html              # Admin Analytics & Inventory Management Panel
├── cart.html                   # Real-time Shopping Cart & Cost Breakdown
├── book now.html               # Express Checkout & Order Confirmation Modal
├── search.html                 # Instant Catalog Search & Keyword Filter
├── add product.html            # New Item Publisher with Real-Time Card Preview
├── product cancelation.html    # Order Cancellation & Return Request System
├── contactme.html              # Developer Bio & Support Inquiry Portal
│
├── Authentication/
│   ├── login.html              # Standard User Login
│   ├── singn in.html           # Dual Mode Sign-In (Password / OTP)
│   ├── singnup.html            # Quick Account Registration with Strength Meter
│   └── creat account.html      # Extended Member Profile Creation
│
├── Apparel & Fashion/
│   ├── shirt.html              # Men's Formal, Casual & Checks Shirts
│   ├── pant.html               # Men's Chinos, Trousers & Relaxed Pants
│   ├── saari.html              # Banarasi, Silk & Party Wear Sarees
│   ├── lehnga.html             # Heavy Bridal & Festive Designer Lehengas
│   └── patiyala.html           # Punjabi Patiala & Dhoti Salwar Suits
│
├── Accessories & Eyewear/
│   ├── cap.html                # Baseball, Snapback & Vintage Caps
│   └── glases.html             # Smart Lenses & Precision Optical Frames
│
├── Stationery, Books & Arts/
│   ├── books.html              # Historical, Literary & Philosophical Books
│   ├── notbook.html            # Hardcover Journals, Registers & Planners
│   ├── pen.html                # Luxury Fountain Pens & Gel Writing Tools
│   └── color brush.html        # Fine Art Acrylic, Mop & Detail Paintbrushes
│
├── Kids & Play/
│   └── toy.html                # Unbreakable Vehicles & STEM Learning Toys
│
├── assets/                     # Media & Image Files
│   └── Raj.jpg                 # Developer Profile Picture
└── README.md                   # Project Documentation
