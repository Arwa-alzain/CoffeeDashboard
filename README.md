# ☕ BrewMaster Dashboard & Weather Integration

**BrewMaster Dashboard** is a modern, responsive admin platform designed for coffee shop management. It combines inventory control and order tracking with a real-time Weather API integration, allowing shop managers to plan their operations and outdoor seating based on live climate data.

The project showcases a clean UI/UX, robust state management, and the practical application of professional React patterns.

---

## 🚀 Project Overview

The BrewMaster Dashboard provides a centralized hub for administrators to manage daily coffee shop operations. Key features include tracking high-demand beverages, monitoring stock levels, and a dedicated weather tool. 

The application uses a modular architecture with a **Protected Routing** system, a dynamic **Sidebar**, and a fully interactive **Main Content Area**.

---

## 🎯 Main Goals

* 📦 **Inventory Management:** Full CRUD (Create, Read, Update, Delete) for coffee products.
* 🧾 **Order Tracking:** Efficient monitoring of customer orders and stock status.
* 🌤️ **Climate Integration:** Real-time weather forecasting to optimize shop hours and seating.
* 💻 **React Best Practices:** Practical use of Hooks, Routing, and Component-based architecture.

---

## 🛠️ Technologies Used

* **React.js** (Functional Components)
* **React Router Dom** (Navigation & Protected Routes)
* **Lucide React** (Modern, lightweight iconography)
* **Open-Meteo API** (Real-time Weather & Geocoding data)
* **CSS3** (Custom styling with a focus on responsiveness)

---

## 🔐 Key Features

### **1. Secure Authentication**
* **Login Page:** Access control with email and password validation.
* **Protected Routes:** Ensures only logged-in admins can access the dashboard.
* **Auto-Redirect:** Automatically sends unauthorized users back to the login screen.

### **2. Store Analytics**
* **State Cards:** Visual summary of Total Orders and Total Products.
* **Real-time Updates:** Statistics reflect changes instantly when products are added or deleted.

### **3. Product & Order Management**
* **Dynamic Modals:** A unified form to add or edit products (Beverages, Desserts, Breakfast).
* **Status Indicators:** Visual "Active" or "Out of Stock" badges based on inventory counts.
* **Image Handling:** Support for product image previews using `URL.createObjectURL`.

### **4. Weather API Integration 🌤️**
* **Smart Search:** Search for any city worldwide with an auto-suggest dropdown.
* **Live Metrics:** Displays temperature (°C), wind speed (km/h), and current local time.
* **UX-Focused:** Features loading spinners and error handling for a smooth API experience.

---

## 📂 Project Structure

```text
src/
├── components/        # Reusable UI (Sidebar, Header, Modals, StateCards)
├── layout/            # DashboardLayouts for structural management
├── pages/             # Main views (Login, ProductPage, OrderPage)
├── API/               # WeatherApi component logic
└── data/              # Initial mock data for orders and products
 ```

---

## 👩‍💻 Author

**Arwa Alzain**

- 📧 Email: [arwaahalzain@gmail.com](mailto:arwaahalzain@gmail.com)
- 💼 LinkedIn: [linkedin.com/in/arwa-alzain](https://www.linkedin.com/in/arwa-alzain/)
- 🐙 GitHub: [github.com/Arwa-alzain](https://github.com/Arwa-alzain)

---

✨ *Feel free to fork the project, explore the code, and experiment with new features.*
