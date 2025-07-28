# Postman_API_Internship_Tasks 🚀

This repository contains a comprehensive Postman collection created as part of my internship training. The tasks demonstrate my understanding of RESTful API testing using **Postman**, covering everything from CRUD operations to variable management, scripting, and assertions.

---

## 🌟 Welcome!
As part of my internship assignment, I was instructed to test a sample API using **all major HTTP methods (GET, POST, PUT, PATCH, DELETE)**. This repository reflects the practical application of those concepts using Postman features such as dynamic variables, pre-request scripts, test scripts, and chained requests.

---

## 📋 Table of Contents
- 📚 About the Repository  
- 🧪 Technologies Used  
- 🔍 Key Features Covered  
- 📁 Repository Structure  
- ⚙️ How to Use  
- 🤝 Credits  
- 📬 Contact  

---

## 📚 About the Repository
This repository showcases my ability to:
- 🔁 Perform complete API testing using CRUD methods
- 🧠 Use pre-request scripts and test scripts for dynamic behavior
- 🔗 Chain APIs by capturing response data from one and using it in another
- 🧪 Write both passing and failing assertions using Postman's Chai Assertion Library
- 🎯 Log parsed values from the response JSON in the Postman Console
- ⚙️ Manage environment variables for clean and maintainable requests

---

## 🧪 Technologies Used
- **Postman** – API client used for testing and automation  
- **JavaScript (Pre-request & Tests)** – For scripting logic in Postman  
- **Chai Assertion Library** – Used for validating API response data  
- **Faker.js (via Postman)** – To generate random test data  
- **REST APIs** – Target for testing methods  

---

## 🔍 Key Features Covered

| Feature | Description |
|--------|-------------|
| **Base URL Variable** | Base URL is stored as an environment variable and reused in all requests |
| **Random Data** | Request body includes dynamically generated values (e.g., name, email) |
| **JSON Parsing** | Response body is parsed and specific properties are logged in the console |
| **Assertions** | Used Chai assertions to validate response data |
| **Failing Test** | A test is deliberately written to fail, for demonstration purposes |
| **Pre-request Script** | Variables are initialized before sending the request |
| **Reset in Tests** | The same variables are reset in the Tests tab after the response |
| **Request Chaining** | Data from one response is stored and reused in a subsequent request |
| **Collection Runner** | The chained APIs run successfully together in sequence |

---

## 📁 Repository Structure

📦 Postman_API_Internship_Tasks/
┣ 📄 API_Test_Collection.json → Postman Collection (with all requests)
┣ 📄 API_Environment_Setup.json → Postman Environment File (with variables)
┗ 📄 README.md → Documentation (this file)



---

## ⚙️ How to Use

1. **Clone this Repository**
```bash
git clone https://github.com/laibakhan412/Postman_API_Internship_Tasks
Open Postman → Import

Import both files:

API_Test_Collection.json

API_Environment_Setup.json

Select Environment

Choose the environment from the top-right dropdown in Postman

Run the Collection

Open the Collection Runner

Execute all requests in sequence

View dynamic console logs, passed/failed tests, and response data

---

## 🤝 Credits
This repository is created as part of my internship program focusing on practical API Testing with Postman. I thank my mentors for guiding me through advanced features like scripting, chaining, and dynamic variable management.

---

## 🌐 LinkedIn: www.linkedin.com/in/laiba-khan-955691264

---

## 📧 Email: klaiba412@gmail.com

Thanks for visiting my API testing project! I hope it serves as a helpful reference for Postman learners and API testers alike. 💡

Happy Testing! 🧪✨
