# 💰 Smart Budget App (Final POE Submission)
**Student:** Msseni Thabethe  
**Module:** Open Source Coding (Intermediate)  
**Module Code:** OPSC6312  
**Date:** November 2025  

---

## 📱 Overview
Smart Budget is a personal finance management Android application that helps users manage income, expenses, and savings goals.  
The app offers **real-time budget alerts**, **offline tracking**, **Google Sign-In**, and **multi-language support** (English + isiZulu).  
It was developed in **Kotlin** using **Firebase**, **RoomDB**, and **GitHub Actions** for automation.

---

## ✨ Features
- 🔐 **Secure Login & Registration** using Firebase Authentication  
- ☁️ **Offline Mode** with RoomDB and automatic sync when online  
- 🧾 **Track Income & Expenses** by category  
- 📊 **Charts and Analytics** for monthly overview  
- 🪪 **Google SSO** (Single Sign-On)  
- 🔔 **Real-Time Notifications** for budget limits via Firebase Cloud Messaging  
- 🌍 **Multi-language support:** English and isiZulu  
- ⚙️ **Automated Build & Testing** with GitHub Actions  

---

## 🧰 Tech Stack
| Technology | Purpose |
|-------------|----------|
| Kotlin | Main programming language |
| Firebase Authentication | Secure user login |
| Firestore | Online database |
| RoomDB | Offline local database |
| Firebase Cloud Messaging | Push notifications |
| GitHub Actions | CI/CD automation |
| XML | UI design layouts |
| Google Sign-In SDK | Single Sign-On |

---

## 🔗 API Overview
| Endpoint | Method | Description |
|-----------|---------|-------------|
| `/expenses` | GET | Retrieve user expenses |
| `/expenses` | POST | Add a new expense |
| `/expenses/{id}` | PUT | Update existing expense |
| `/expenses/{id}` | DELETE | Delete expense |

The API is hosted via **Firebase Cloud Functions**.

---

## 🚀 How to Run
1. Clone this repository:  
   ```bash
   git clone https://github.com/<your-username>/SmartBudgetApp_OPSC6312_Part3.git
