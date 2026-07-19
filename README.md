# Automation Exercise API Testing

## Overview

This project showcases end-to-end REST API testing for the **Automation Exercise** application using **Postman** and **Newman**. It covers functional validation, request and response verification, error handling, and automation of API test execution through comprehensive positive and negative test scenarios.

---

## Project Scope

The project covers testing of the following API modules:

- Products
- Brands
- Product Search
- User Authentication
- User Registration
- User Account Management
- User Profile Retrieval

---

## Objectives

- Validate REST API functionality.
- Verify supported and unsupported HTTP methods.
- Validate request parameters and response payloads.
- Verify HTTP status codes and error messages.
- Perform positive and negative API testing.
- Validate response headers and response time.
- Automate API execution using Newman.

---

## Technologies & Tools

| Category | Technology |
|----------|------------|
| API Client | Postman |
| API Runner | Newman |
| API Type | REST API |
| Data Format | JSON |
| Protocol | HTTP |
| Testing | Functional API Testing |
| Reporting | Newman Report |

---

## API Test Coverage

| Module | Scenarios |
|---------|-----------|
| Products | Get All Products, Invalid POST Request |
| Brands | Get All Brands, Invalid PUT Request |
| Search | Product Search, Missing Parameter Validation |
| Authentication | Valid Login, Invalid Login, Missing Email, Invalid HTTP Method |
| User Account | Create Account, Update Account, Delete Account, Get User Details |

---

## Validation Performed

- ✅ Functional Validation
- ✅ Positive Testing
- ✅ Negative Testing
- ✅ HTTP Method Validation
- ✅ Request Parameter Validation
- ✅ Response Body Validation
- ✅ Response Header Validation
- ✅ Status Code Validation
- ✅ Response Time Validation
- ✅ Error Message Validation
- ✅ CRUD Operations Validation

---

## Repository Structure

```text
automation-exercise-api-testing/
│
├── Collections/
├── Environment/
├── Reports/
├── Screenshots/
├── Test Cases/
└── README.md
```

---

## Execution

Run the collection using Newman:

```bash
newman run AutomationExercise.postman_collection.json \
-e AutomationExercise.postman_environment.json
```

---

## Author

**Muhammed Raafat**

Software Testing Engineer
