# Chinatown Mobile POS (Point of Sale System)

> 📦 A lightweight POS system built for mobile stores in Australia — designed as a learning project during spare time.

## 📌 Project Overview

Chinatown Mobile POS is a foundational point-of-sale (POS) system tailored for small mobile phone stores operating in Australia. It is still under development and not yet production-ready. This project is developed as a hobby while learning and practicing software development skills.

Although basic structures are in place, **many features are still incomplete or need refinement**.

## ✅ Features (Implemented or Partially Implemented)

- **🧾 Daily Sale Tracking**  
  Record and summarize daily transactions by type and payment method.

- **📄 Contract Management**  
  Handle customer contracts, plans, and associated devices with key details like IMEI, plan type, and discounts.

- **📦 Stock Management**  
  Track device and SIM card inventory with supplier and IMEI data.

- **🧮 Invoice & Items**  
  Generate and store invoice records with itemized product lines and GST calculations.

- **👨‍💼 Staff Management**  
  Store staff profiles, login credentials, and assign roles (Manager, Staff, Viewer).

## 📁 Folder Structure (Key)

- `Models/` – Entity definitions for database structure
- `Data/` – `AppDbContext` and EF Core configuration
- `Forms/` – Windows Forms UI components (WIP)
- `Helpers/` – Database factory and utility classes

## 🚧 To-Do (Planned Improvements)

- Add user authentication & role-based access control
- Complete reporting features (monthly summaries, staff KPI)
- Improve error handling and input validation
- Refactor Forms for better UI/UX and performance

## 💡 Motivation

This project started as a personal experiment to better understand .NET development, EF Core, and building desktop applications using Windows Forms. It combines practical store-use cases with hands-on coding practice.

## ⚠️ Disclaimer

This is a **personal learning project** and is **not intended for commercial use at this stage**. Feedback and suggestions are welcome!

# PosSystem
A POS system designed for Australian mobile stores (with Windows Forms)
