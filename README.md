# 🌿 Paradise Nursery – Online Plant Shopping Application

**Paradise Nursery** is a modern, user-friendly online plant shopping application built with React and Redux Toolkit. It provides a seamless shopping experience where users can explore a variety of houseplants, discover their benefits, and manage their shopping cart efficiently.

The application is designed to make online plant shopping simple, interactive, and enjoyable.

## 🌱 Project Overview

Paradise Nursery offers a curated collection of houseplants organized into different categories, helping users easily find plants that suit their preferences and needs.

Users can browse products, view plant details and prices, add plants to their shopping cart, update quantities, and review their total purchase amount.

## ✨ Key Features

### 🏡 Landing Page
- Attractive landing page introducing Paradise Nursery.
- Company background and information.
- Get Started button for easy navigation to the shopping experience.

### 🌿 Product Listing
- Displays a collection of houseplants organized into multiple categories.
- Each product includes an image, name, description, and price.
- Add to Cart functionality for individual products.
- Prevents duplicate additions by disabling the button after a product is added.
- Dynamically updates the shopping cart item count.

### 🛒 Shopping Cart
- Displays all selected plants with product images and pricing details.
- Increase or decrease product quantities.
- Automatically calculates individual item subtotals.
- Dynamically updates the total cart amount.
- Remove unwanted products from the cart.
- Continue Shopping option to return to the product listing.
- Checkout functionality with a Coming Soon notification.

### 🔄 State Management
- Uses Redux Toolkit to manage shopping cart state.
- Implements reusable reducers for adding, removing, and updating product quantities.
- Keeps cart information synchronized across application components.

### 📱 Navigation
- Consistent navigation bar across the shopping application.
- Navigation links for Home, Plants, and Cart.
- Dynamic shopping cart indicator showing the total number of items.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| React.js | Building reusable and interactive UI components |
| JavaScript (ES6+) | Application logic and functionality |
| Redux Toolkit | Global state management |
| CSS3 | Styling and responsive layouts |
| HTML5 | Application structure |
| Vite | Development server and build tooling |
| Git & GitHub | Version control and project hosting |

## 📂 Project Structure

```text
e-plantShopping/
│
├── public/
│
├── src/
│   ├── components/
│   │   ├── AboutUs.jsx
│   │   ├── ProductList.jsx
│   │   └── CartItem.jsx
│   │
│   ├── redux/
│   │   └── CartSlice.jsx
│   │
│   ├── App.jsx
│   ├── App.css
│   └── main.jsx
│
├── index.html
├── package.json
├── package-lock.json
├── vite.config.js
└── README.md
```

*Note: Adjust the folder structure above if your actual project uses different file locations.*

## 🚀 Getting Started

Follow these steps to run the application locally.

### Prerequisites

- Node.js
- npm
- Git

### Installation

**1. Clone the repository**

```bash
git clone https://github.com/adonjoseph345-creator/e-plantShopping.git
```

**2. Navigate to the project directory**

```bash
cd e-plantShopping
```

**3. Install dependencies**

```bash
npm install
```

**4. Start the development server**

```bash
npm run dev
```

**5. Open the application**

Open the local URL displayed in your terminal, usually:

```text
http://localhost:5173/
```

## 🎯 Project Objectives

- Develop an interactive e-commerce application using React.
- Understand component-based architecture and reusable UI development.
- Implement global state management using Redux Toolkit.
- Handle dynamic shopping cart operations.
- Improve frontend development and user experience design skills.

## 🔮 Future Enhancements

- User authentication and account management.
- Secure payment gateway integration.
- Product search and filtering.
- Product reviews and ratings.
- Order tracking and purchase history.
- Backend integration and database connectivity.

## 👨‍💻 Author

**Adon Joseph**

GitHub: [@adonjoseph345-creator](https://github.com/adonjoseph345-creator)

## 📄 License

This project is licensed under the Apache-2.0 License.

---

**Paradise Nursery – Bring Nature Home! 🌿**

