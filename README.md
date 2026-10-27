## MSM E-Commerce Platform

A full-stack e-commerce platform built with Next.js and Supabase. Developed 6 months ago, this project provides capability of handling up to 5,000 products, automated media fetching, stock tracking, and a direct checkout flow via WhatsApp.

## 🚀 Key Features

* **5,000 Product Capacity:** Engine can store, filter, and display up to 5,000 product listings without drops in page speed.
* **Stock Management:** Simple built-in tracking for inventory to assign stock-in and stock-out movements.
* **Auto-Fetch Images:** Integrated directly with the Pixabay API to automatically pull product images.
* **CSV Bulk Import:** Upload your entire product CSV at once using standard CSV file imports.
* **WhatsApp Ordering:** Skips complex checkouts. Orders generate a structured text message and send it directly to the merchant's WhatsApp.
* **Admin Portal:** A simple backend panel to add new items, delete old ones, or change product prices.

## 🛠️ Tech Stack

* **Framework:** Next.js
* **Database & Backend:** Supabase (PostgreSQL)
* **Media Automation:** Pixabay API

## ⚠️ Current Flaws & Limitations

This project was built as a functional prototype. Please note these security issues before trying to deploy it in production:

* **No RLS Policies:** Row Level Security (RLS) is not configured inside Supabase. Database tables are open for public queries.
* **No Authentication:** There is no user signup or login system for clients or admins.
* **Password-Only Control:** All admin operations (adding, editing, and deleting products) are protected by a single shared admin password instead of secure login sessions.

## 📦 Getting Started

### Prerequisites

* Node.js installed on your machine
* A Supabase account and database project
* A Pixabay API key

### Setup & Installation

1. **Clone the repository:**
2. **Install the dependencies:**
   ```bash
   npm install
   ```

3. **Configure Environment Variables:**
   Use Your own database to keep things secure

4. **Run the application:**
   ```bash
   npm run dev
   ```

## 📄 License

This project is licensed under the MIT License.
