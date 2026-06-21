# 🍽️ TableTap

A high-performance, full-stack campus dining platform designed to eliminate physical counter congestion through asynchronous order routing, real-time preparation tracking, and automated counter-pickup notifications.

---

## 🚀 Core Features

* **Seat-to-Counter Ordering:** Students can browse live menus, customize dishes, and place orders directly from their seats.
* **Real-Time Status Pipeline:** Live preparation tracking updates students on whether their meal is *Pending*, *In the Kitchen*, or *Ready for Pickup*.
* **Instant Notifications:** Automated alerts notify students the exact second their order is ready, preventing counter crowding.
* **Vendor Dashboard:** An intuitive management console for canteen vendors to track live inventory, update menu availability, and manage active order queues.

---

## 🛠️ Tech Stack & Architecture

* **Frontend:** React.js, Tailwind CSS, shadcn/ui
* **Backend:** Node.js, Express.js
* **Database:** MongoDB (Structured document storage for orders, users, and menu items)
* **State & Real-time Sync:** Localized API state management with robust error boundaries

---

## ⚙️ Local Development Setup

### Prerequisites
* Node.js (v18 or higher)
* MongoDB database instance

### 1. Clone & Navigate
```bash
git clone [https://github.com/Auranzeb05/TableTap.git](https://github.com/Auranzeb05/TableTap.git)
cd TableTap

