```markdown
# Nxt Trendz - Cart Features 🛒

A fully functional e-commerce cart module built with **React.js** as part of the Nxt Trendz application. This feature enhances the shopping experience by handling cart operations, authentication-based access, and dynamic cart updates.

---

## 🚀 Features

- **Authentication-based Routing**
  - Unauthenticated users trying to access the Cart route are redirected to the Login page.

- **Cart Management**
  - Add products to the cart.
  - Adding the same product multiple times updates its quantity instead of creating duplicates.
  - Remove individual cart items.
  - Remove all items from the cart in one click.
  - Displays an empty cart view when no items are present.

- **Quantity Controls**
  - Increment and decrement product quantities.
  - Remove product automatically when quantity reaches zero.
  - Product prices update dynamically based on quantity.

- **Cart Summary**
  - Displays total items and total amount in the cart.
  - Updates dynamically as items are added, removed, or updated.

- **Responsive Design**
  - Optimized for mobile, tablet, and desktop screens.

---

## 📂 Project Structure

```

src/
├── App.js
└── components/
├── Cart/
│   ├── index.js
│   └── index.css
├── CartItem/
│   ├── index.js
│   └── index.css
└── CartSummary/
├── index.js
└── index.css

````

---

## 🛠️ Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone <repository-url>
   cd nxt-trendz-cart-features
````

2. **Install Dependencies**

   ```bash
   npm install
   ```

3. **Start the Application**

   ```bash
   npm start
   ```

The app will run on [http://localhost:3000](http://localhost:3000).

---

## 📸 Screenshots

### Cart Page (Desktop)

![Cart Desktop](https://assets.ccbp.in/frontend/content/react-js/nxt-trendz-cart-features-lg-output.png)

### Cart Page (Mobile)

![Cart Mobile](https://assets.ccbp.in/frontend/content/react-js/nxt-trendz-cart-features-sm-output-v0.png)

### Empty Cart View

![Empty Cart](https://assets.ccbp.in/frontend/content/react-js/nxt-trendz-cart-features-empty-cart-view.png)

---

## 🎨 Resources

* **Colors**

  * Primary Blue: `#0b69ff`
  * Dark Blue: `#171f46`
  * Gray: `#616e7c`
  * White: `#ffffff`

* **Font**

  * [Roboto](https://fonts.google.com/specimen/Roboto)

---

## ⚡ Tech Stack

* React.js
* React Router
* Context API
* React Icons
* CSS3 (Responsive Styling)

---

## 🧑‍💻 Author

Developed with ❤️ using React.js

```
```
