# 🛍️ Simple E-Commerce Cart (Frontend Project)

## 🧾 Description:
This is a simple e-commerce cart application created using:
- **HTML5**
- **CSS (Bootstrap 5)**
- **JavaScript (ES6+)**
- **LocalStorage** for client-side persistence

Users can:
- Browse a list of products
- Add items to the cart
- Complete a purchase
- View their account report and status
- Confirm or cancel the purchase

---

## 📁 Pages:

| File           | Description                              |
|----------------|------------------------------------------|
| `products.html`| Main product list with add to cart       |
| `cart.html`    | Shows selected items and total           |
| `account.html` | Purchase summary + confirm/cancel/report |
| `login.html`   | User login with dummy credentials        |
| `data.json`    | Contains product and user data           |

---

## 📦 Features:

- ✅ Dynamic product rendering from JSON
- ✅ Cart calculation with quantity and price
- ✅ Purchase confirmation system
- ✅ User login simulation
- ✅ Account page shows status: `"Pending Payment"` or `"Paid"`
- ✅ Order history toggle using Bootstrap Collapse
- ✅ Confirm button for unpaid orders
- ✅ Theme switcher: 🌙/☀️ dark & light mode
- ✅ Logout button on all pages
- ✅ Responsive UI with Bootstrap

---

## 👤 User Flow:

1. User logs in from `login.html`
2. Gets redirected to `products.html`
3. Adds products to cart ➜ opens `cart.html`
4. Confirms purchase ➜ redirect to `account.html`
5. Can confirm payment or cancel
6. Can view full order history (paid & pending)

---

## 🛠️ Technologies Used:
- **Bootstrap 5**: layout, components, responsive UI
- **JavaScript**: dynamic DOM, events, localStorage
- **Fake API**: data loaded from `data.json`

---

## 🔐 Sample Users:

```json
{
  "username": "user1",
  "password": "123"
}
