<p align="center">
  <img src="https://automationexercise.com/static/images/home/logo.png" alt="Automation Exercise Logo">
</p>

# Automation Exercise API Testing

## Overview

This project demonstrates comprehensive REST API testing for the **Automation Exercise** application using **Postman** and **Newman**. It validates API functionality, request methods, response status codes, response payloads, and error handling through positive and negative test scenarios.

---

## Project Objectives

- Validate REST API functionality.
- Verify HTTP methods (GET, POST, PUT, DELETE).
- Validate response status codes and response body.
- Verify API behavior under valid and invalid scenarios.
- Perform positive and negative API testing.
- Automate API execution using Newman.

---

## Technologies Used

- Postman
- Newman
- REST API
- JSON
- HTTP Methods
- API Testing

---

## APIs Covered

| API | Endpoint | Method | Expected Response |
|------|----------|--------|------------------|
| API 1 | `/productsList` | GET | Retrieve all products (200) |
| API 2 | `/productsList` | POST | Method Not Allowed (405) |
| API 3 | `/brandsList` | GET | Retrieve all brands (200) |
| API 4 | `/brandsList` | PUT | Method Not Allowed (405) |
| API 5 | `/searchProduct` | POST | Search products successfully (200) |
| API 6 | `/searchProduct` | POST | Missing parameter validation (400) |
| API 7 | `/verifyLogin` | POST | Verify login with valid credentials (200) |
| API 8 | `/verifyLogin` | POST | Missing email validation (400) |
| API 9 | `/verifyLogin` | DELETE | Method Not Allowed (405) |
| API 10 | `/verifyLogin` | POST | Invalid credentials validation (404) |
| API 11 | `/createAccount` | POST | Create user account (201) |
| API 12 | `/deleteAccount` | DELETE | Delete user account (200) |
| API 13 | `/updateAccount` | PUT | Update user account (200) |
| API 14 | `/getUserDetailByEmail` | GET | Retrieve user details (200) |

---

## Test Coverage

- ✅ Functional Testing
- ✅ Positive Testing
- ✅ Negative Testing
- ✅ Status Code Validation
- ✅ Response Body Validation
- ✅ Response Header Validation
- ✅ Response Time Validation
- ✅ HTTP Method Validation
- ✅ Missing Parameter Validation
- ✅ Invalid Credentials Validation
- ✅ User Account CRUD Operations

---

## Repository Structure
