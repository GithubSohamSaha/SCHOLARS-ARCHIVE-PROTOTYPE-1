# Scholar's Archive – Prototype 1

Scholar's Archive is a static, role‑based Library Management System prototype built with plain HTML, CSS, and JavaScript. It simulates how different stakeholders (Users, Librarians, Stock Managers, Accountants) interact with a library system—running entirely in the browser using `localStorage`.

Because it is 100% front‑end, it can be hosted easily on GitHub Pages and accessed from anywhere.

---

## 🚀 Live Demo

Once GitHub Pages is enabled for this repository, the app will be available at:  
**`https://githubsohamsaha.github.io/SCHOLARS-ARCHIVE-PROTOTYPE-1/`**

---

## ✨ Features

### 👥 Multiple Roles
* **User** – Search and borrow books, view borrowed history, pay fines.
* **Librarian** – View all books, all users, fines, stock overview, and issue books.
* **Stock Manager** – Add new book data, raise stock order requests, and see stock alerts.
* **Accountant** – Manage fines, view fine reports, acknowledge payments, and issue receipts.

### 🔐 Authentication (Demo)
* Login form with role selection.
* Sign‑up form to create new accounts for any role.
* Session persistence using `localStorage` so page reloads keep you logged in.

### 📚 Core User Flows
* **Book Catalogue:** Search with filters on title, author, and subject.
* **Borrow/Return:** Automatic fine calculation for late returns.
* **Payments:** Simple "payment gateway" modal (simulated) for individual or "pay all" fine options.
* **Dashboards:** Role-specific menus and overview data.

### 🔄 Multi-Tab Sync
* Data (books, borrows, fines, users) is stored in `localStorage` and synced across tabs using the `storage` event.
* *Example:* If an Accountant issues a fine in one tab, the User tab updates automatically without a refresh.

### 🌐 Public Pages
* **Home** – Overview and quick start guide.
* **Support / FAQs** – Role guidance with buttons that pre-select roles for login.
* **Contact** – Static contact info and a demo contact form.

---

## 🛠 Tech Stack

* **HTML5** – Structure (`index.html`)
* **CSS3** – Layout and styling (`style.css`)
* **Vanilla JavaScript** – Logic, role handling, and data simulation (`script.js`)
* **localStorage** – Persistent demo "database" in the browser.
* **No Backend** – No server or real database required.

---

## 📁 Project Structure

```text
> The static prototype runs entirely from index.html + script.js + style.css.
> The backend/ folder is not required for this static demo.
