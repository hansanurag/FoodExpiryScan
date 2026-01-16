# 🍽️ FoodExpiryScan  
A smart web application to track food and medicine expiry dates using **barcode scanning**, **image upload**, and **inventory management**.  
Designed to reduce waste and help users stay organized with clean UI and dark/light themes.

---

## 🚀 Features

### 🔍 Barcode Scanning  
Scan any product barcode using your device camera. The system auto-fills item details and expiry date.

### 🖼️ Image Upload – Expiry Detection  
Upload an image of a product packaging, and the app detects expiry date (demo logic).  
Auto-fills item form on detection.

### 📦 Inventory Management  
- Add food & medicine items  
- Track quantity, storage type, and expiry  
- Category-wise filtering  
- Shows status: **Safe**, **Expiring Soon**, **Expired**

### 🌙 Theme Toggle  
Switch between **Dark Mode** and **Light Mode** with one click.  
Your preferred theme is saved automatically.

### 💾 Backup Data  
Download your entire inventory as a **JSON file** for backup or migration.

### 🔐 Authentication
- Register & Login  
- JWT-based secure authentication  
- Token stored in browser (persistent login)

---

## 🛠️ Tech Stack

### **Frontend**
- HTML  
- CSS (custom dark UI)  
- JavaScript  
- LocalStorage  
- QuaggaJS (Barcode Scanner)

### **Backend**
- Node.js  
- Express.js  
- MongoDB (Mongoose)  
- JWT Authentication  
- Multer / File Handling (optional)

---

## 📂 Project Structure

