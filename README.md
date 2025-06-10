# 🧮 Lot Price Calculator App

A mobile-ready real estate calculator app designed to compute Total Contract Price, apply discounts, add title fee, and calculate monthly payments over a 36-month, 0% interest term. Built using modern web technologies and packaged for Android/iOS using Capacitor.

---

## 📲 Features

- 📐 Lot Area × Price per sqm = Total Contract Price (TCP)
- 💸 Apply optional **Discount** and **Reservation Fee**
- 📑 **Title Fee** inclusion for complete cost estimate
- 🧾 Monthly amortization over 36 months (0% interest)
- ₱ Currency formatting
- ✅ Mobile-first layout and clean UI

---

## ⚙️ Tech Stack

- **Framework:** HTML, CSS, JavaScript
- **Build Tools:** Vite + TailwindCSS
- **Capacitor:** Native wrapper for Android/iOS
- **IDE:** Android Studio
- **Package Manager:** npm
- **Deployment Support:** Netlify

---

## 🚀 Getting Started

### 📦 Installation

```bash
git clone https://github.com/your-username/lot-price-pilot-app-shad.git
cd lot-price-pilot-app-shad
npm install

## 🔧 Development Server
npm run dev

## 📱 Build for Production & Mobile
npm run build
npx cap sync
npx cap add android    # or ios
npx cap run android    # or ios
