# Create User API Test Suite

This repository contains a comprehensive set of **Postman API tests** for the `Create User` API provided by Automation Campus.

## 📌 Project Overview
The goal of this project is to validate the **Create User API** from different angles, including:
- Successful user creation
- Duplicate data handling
- Input validation (missing/invalid fields)
- Header and authentication handling
- Content type validation

All tests were built and executed in **Postman**.

---

## 🧪 Test Cases Implemented

| #   | Test Name            | Purpose / What It Checks                                    |
|-----|----------------------|------------------------------------------------------------|
| 1   | Used Mail            | Duplicate email is rejected (400 Bad Request)               |
| 2   | Authentication       | Missing roll number header returns unauthorized (401)       |
| 3   | Used Number          | Duplicate phone number is rejected (400 Bad Request)        |
| 4   | Change User Name     | Attempt to change after creation (should be handled safely) |
| 5   | Phone Number Break   | Invalid or missing phone number is rejected (400)           |
| 6   | Email Break          | Invalid or missing email is rejected (400)                  |
| 7   | First Name Break     | Missing first name returns error (400)                      |
| 8   | Last Name Break      | Missing last name returns error (400)                       |
| 9   | Invalid Content Type | Wrong content type returns error (415 or similar)           |
| 10  | Invalid Roll Number  | Invalid roll number returns unauthorized (401)              |
| 11  | Duplicate User       | Same email and phone together returns error (400)           |

---

## 📂 Repository Contents
- `CreateUserAPI.postman_collection.json` — Postman collection containing all test cases.

---

## 🚀 How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/neilmandlik/CreateTestApi.git
