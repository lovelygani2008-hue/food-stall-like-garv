# 📚 ChapterOne — Online Bookstore

A responsive, interactive **Online Bookstore** web application built using pure **HTML5, CSS3, and Vanilla JavaScript**. Designed with zero external dependencies and pure CSS 3D book covers, the site runs seamlessly both online (via GitHub Pages) and 100% offline.

🔗 **Live Demo:** `https://your-username.github.io/online-bookstore/`

---

## ✨ Key Features

- **Book Categories:** Browse 15 curated titles across 6 genres — *Anime & Manga*, *Action*, *Romance*, *Sci-Fi & Fantasy*, *Mystery & Thriller*, and *Self-Help*.
- **Featured Bestsellers & Deal of the Day:** Highlights top-rated titles with MRP, selling price (in ₹), and automatic discount percentage badges.
- **Live Search & Sorting:** Filter books instantaneously by title, author, or genre, and sort by **Price (Low to High / High to Low)** or **Top Rated**.
- **Popular Authors Section:** Click any featured author to filter and view their books in the shopping section.
- **Interactive Shopping Cart Drawer:** Add books, update quantities, remove items, and view automatic **Free Delivery on orders above ₹499** (₹49 below). Cart data persists via `localStorage`.
- **Working Offers & Coupon Codes:** Apply live discounts directly inside the cart or via one-click offer cards.
- **Wishlist & Quick-View Modal:** Save favourite books to a dedicated Wishlist filter and click any book cover to preview page count, rating, and synopsis.
- **Complete Checkout Flow:** Validates customer delivery details, supports **UPI, Debit/Credit Cards, and Cash on Delivery**, and generates a unique Order ID (`CH1-XXXXXX`).
- **Light & Dark Mode Toggle:** Smooth theme switching with saved user preference.
- **100% Offline-Ready UI:** All 3D book covers are styled in pure CSS—no external image links that can break during demos.

---

## 🎟️ Working Coupon Codes (For Demo & Testing)

| Coupon Code | Discount | Usage |
| :--- | :--- | :--- |
| `READ20` | Flat **20% OFF** | Valid on entire cart |
| `STUDENT15` | Flat **15% OFF** | Student special discount |

---

## 🛠️ Tech Stack

- **HTML5** — Semantic structure, accessible modals, and forms
- **CSS3** — CSS Grid, Flexbox, CSS Variables for Light/Dark theming, responsive media queries, and 3D book cover styling
- **JavaScript (ES6+)** — Dynamic DOM rendering, live search/sorting, cart & coupon calculations, and `localStorage` persistence

---

## 📂 Project Structure

```text
online-bookstore/
├── index.html      # Main webpage structure and interactive JavaScript logic
├── style.css       # Complete styling, responsive breakpoints, and dark/light themes
└── README.md       # Project documentation
