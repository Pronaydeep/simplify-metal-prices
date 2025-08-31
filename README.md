# 🪙 Simplify Metal Prices - React App

A clean, responsive React application that displays **live 24K prices** of metals — **Gold, Silver, Platinum, Palladium** — along with detailed views and fallback loaders for individual API fetches. Built using **React, Vite, and plain CSS**.

> 🔗 [Live Demo](https://Pronaydeep.github.io/simplify-metal-prices)

---

## 🧠 Features

- ⏱️ Real-time pricing for 4 metals
- 📦 Data loaded from [GoldAPI.io](https://goldapi-a4to19meviaah0-io/)
- 🧭 Independent loading states for each metal card
- 🔁 Full error handling & fallback logic
- 👁️ Detail page showing:
  - Metal name
  - 24K price
  - Previous open & close
  - Timestamp and date
- ⚛️ Navigation with React Router
- 💅 Styled using **vanilla CSS** (no Tailwind)

---

## 📸 Screenshots

### 🏠 Home Page
> Shows all 4 metals with price and timestamp
![Home Screenshot](./screenshots/home.png)

### 📄 Detail Page
> Shows previous close, open, timestamp, etc.
![Details Screenshot](./screenshots/details.png)

---

## 🚀 Tech Stack

- React
- Vite
- React Router DOM
- Plain CSS
- GoldAPI
- GitHub Pages (for deployment)

---

## 🛠️ Installation

```bash
git clone https://github.com/Pronaydeep/simplify-metal-prices.git
cd simplify-metal-prices
npm install
npm run dev
