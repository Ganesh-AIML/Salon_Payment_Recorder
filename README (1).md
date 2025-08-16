

---

# 💇‍♀️ Salon Payment Record System

A **lightweight, modern web application** to seamlessly record salon payments.
This project features a **beautiful UI for payment entry** and a **success page** with animations and tracking details.
All records are stored securely via **Google Apps Script & Google Sheets integration**.

---

## 🚀 Features

* 🎨 **Elegant UI/UX** – gradient background, smooth animations & floating shapes
* 💳 **Payment Mode Options** – Online / Cash
* 🔒 **Secure Data Storage** – saved directly to Google Sheets via Apps Script
* ✅ **Success Page** – confirmation with date, time & confetti animation
* 📱 **Fully Responsive** – works on desktop, tablet & mobile
* ⏳ **Auto Redirect** – payment entry → success page seamlessly

---

## 📂 Project Structure

```
salon-payment-record/
├── payment.html   # Main payment entry form  
├── thankyou.html  # Success confirmation page  
```

---

## 🛠️ Technologies Used

* **HTML5** → structure
* **CSS3** → responsive design & animations
* **JavaScript (Vanilla)** → form handling & Apps Script integration
* **Font Awesome** → icons

---

## ⚡ Workflow

1. User enters the **payment amount** and selects a **payment method**.
2. Data is submitted via `fetch()` to the **Google Apps Script Web App URL**.
3. On successful submission:

   * Record is stored in **Google Sheets**.
   * User is redirected to the **Thank You page** with animations & payment details.

---

## 📸 Screenshots



### Payment Page
![Payment Page](./Screenshot%202025-08-16%20174214.png)

### Success Page
![Success Page](./Screenshot%202025-08-16%20174242.png)

---

## 🔧 Setup Guide

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/Salon_Payment_Recorder.git
   ```

2. Open **payment.html** in your browser.

3. Inside `payment.html`, update the script URL:

   ```js
   const scriptURL = "YOUR_GOOGLE_APPS_SCRIPT_URL";
   ```

4. Deploy your **Google Apps Script** as a **Web App** linked to Google Sheets.

---

## 👨‍💻 Developer

Developed with ❤️ by **Ganesh Singh** ✨

---


