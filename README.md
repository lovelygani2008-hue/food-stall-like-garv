# 🛵 FeastExpress — Food Delivery & Live GPS Tracking

A responsive **Food Delivery** web application built with **HTML5, CSS3, and Vanilla JavaScript**, featuring restaurant cards, category filters, famous regional dishes with their cities of origin, promo coupons, an interactive cart drawer with GST & delivery calculation, and a live delivery route tracking modal with browser GPS support.

🔗 **Live Demo:** [https://lovelygani2008-hue.github.io/food-stall-like-garv/](https://lovelygani2008-hue.github.io/food-stall-like-garv/)

---

## ✨ Key Features

- **Famous Foods & Where They Are Famous:** Highlights iconic regional dishes and their places of origin (such as *Hyderabadi Chicken Dum Biryani*, *Crispy Ghee Masala Dosa*, *Old Delhi Butter Chicken*, *Mumbai Butter Pav Bhaji*, *Amritsari Royal Paneer Thali*, and *Darjeeling Steamed Momos*) with one-click ordering.
- **Food Categories & Restaurant Cards:** Filter dishes across categories (*Biryani*, *South Indian*, *North Indian*, *Street Food*, *Pizza & Burgers*, *Asian & Momos*, *Desserts*) or click any of the 6 partner restaurants to view its menu.
- **Live Search, Pure Veg Toggle & Sorting:** Search by dish name, restaurant, or famous city, toggle **Pure Veg Only**, and sort by **Price (Low to High / High to Low)** or **Top Rated**.
- **Location Picker & Browser GPS Access:** Choose a delivery city or use **Use GPS** / **Sync My GPS** to fetch device coordinates.
- **Interactive Order Cart & Billing:** Add or adjust item quantities, apply coupon codes, see automatic **Free Delivery above ₹399** (₹39 below), and calculate **5% GST** live.
- **Live Delivery Tracking Map:** Track order stages (*Confirmed*, *Preparing*, *On the Way*, *Delivered*) with an animated SVG route map, ETA and distance updates, delivery partner details, and a **Next Stage ▶** demo control.

---

## 🎟️ Working Coupon Codes

| Coupon Code | Offer | Condition |
| :--- | :--- | :--- |
| `FEAST100` | Flat **₹100 OFF** | Orders of ₹299 or above |
| `SAVE20` | Flat **20% OFF** | Applicable on cart items |
| `FREEDEL` | **Free Delivery** | Waives the ₹39 delivery fee |

---

## 🛠️ Tech Stack

- **HTML5** — Semantic layout, modals, forms, and inline SVG route map
- **CSS3** — Flexbox, CSS Grid, sticky navigation, slide-over cart drawer, and responsive media queries
- **JavaScript (ES6+)** — Dynamic rendering, live filtering/sorting, cart & coupon billing, Geolocation API integration, and `localStorage` persistence

---

## 📂 Repository Structure

```text
food-stall-like-garv/
├── index.html      # Main page structure and interactive JavaScript logic
├── style.css       # Styling, layout grids, modals, and responsive rules
└── README.md       # Project documentation
