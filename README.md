# 🚀 API Testing Project - Reqres

## 📌 Overview

This project demonstrates API testing using Postman, including authentication handling, environment configuration, and automated test validation.

---

## ✨ Features

* Environment variables (DEV)
* Authentication handling (token-based)
* Basic API test automation
* Positive and negative test cases

---

## 🧪 Test Cases

### ✅ Positive Cases

* GET users list
* GET single user
* POST create user
* PUT update user
* DELETE user

### ❌ Negative Cases

* GET user not found (404 validation)

---

## ⚙️ How to Run

1. Import the collection into Postman
2. Import the environment (DEV)
3. Select the environment in Postman
4. Run requests manually or using Collection Runner
5. (Optional) Run with Newman CLI

---

## 🌐 API Used

* Reqres API: https://reqres.in

---

## 📂 Project Structure

```
API_Testing_Proj/
│
├── Collections/
│   └── Pruebas_API_1.postman_collection.json
│
├── Environments/
│   └── Dev.postman_environment.json
│
├── Scripts/
│   └── run_collection.sh
│
└── README.md
```

---

## 📈 Future Improvements

* Add QA environment
* Integrate Newman reports (HTML/JSON)
* CI/CD pipeline integration (GitHub Actions)
* Increase negative test coverage

---
