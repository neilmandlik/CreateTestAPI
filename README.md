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
| 6   | Email Break          |
