
# 🍽️ Online Menu Builder

![Build](https://img.shields.io/badge/build-passing-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Angular](https://img.shields.io/badge/angular-18-dd0031.svg)


**Online Menu Builder** is a modern web application that allows restaurants to easily create, manage, and publish beautiful digital menus online.  

---

## 🚀 Features

### 🌟 Core Features

- **Item Management**
  - Add, edit, and remove menu items
  - Categorize items with custom icons
  - Upload images via drag & drop

- **Menu Creation**
  - Create multiple menus (e.g., breakfast, lunch, dinner)
  - Assign items to menus and reorder
  - Set active days using a weekly calendar

- **Public Menu Viewer**
  - Share a beautiful public menu link with customers
  - Fully responsive and mobile-friendly

- **User Authentication**
  - Signup/login for restaurant owners
  - OTP-based email verification

- **Dashboard & Settings**
  - Manage menus, items, and restaurant settings
  - Preview menus before publishing

---

## 🖼️ Screenshots

Here is some of app pages screenshots.

### Dashboard

![Dashboard Screenshot](assets/screenshots/dashboard.png)

---

### Item Management

![Item Management Screenshot](assets/screenshots/items.png)

---

### Menu Creation

![Menu Creation Screenshot](assets/screenshots/menu-creation.png)

---

### Public Menu Viewer

![Public Menu Screenshot](assets/screenshots/public-menu.png)

---

## ⚙️ Tech Stack

- **Frontend:** Angular, TypeScript, SCSS
- **Components:** Ant Design (ng zorro), custom UI components
- **State Management:** Angular services, rxjs

---

## 💡 How It Works

1. **Sign Up & Login**
   - Restaurant owners sign up and verify via OTP.
2. **Manage Items**
   - Add new dishes, set prices, images, and categories.
3. **Create Menus**
   - Combine items into menus, set display order, and select active days.
4. **Preview & Publish**
   - Share a public link with customers.

---

## 📁 Project Structure

```
src/
├── app/
│   ├── main/         # Core services, auth, interceptors
│   ├── shared/       # Reusable UI components
│   ├── user/         # User-specific features (menus, dashboard)
│   └── app.module.ts
├── public/           # Icons, images, screenshots
├── styles.scss       # Global styles
```

---

## 💻 Installation

```bash
# Install dependencies
npm install

# Run development server
ng serve

# Build for production
ng build
```

---

## ✅ Future Improvements

- Add online ordering directly from public menu
- Analytics for views and orders
- Export menus as PDFs
- Multi-language support

---

## 💬 Contributing

Pull requests and feature suggestions are welcome!  

---

## 💌 Contact

If you'd like to collaborate or have questions, feel free to reach out via email or GitHub issues.

---

### ⭐ If you like this project, please give it a star!
