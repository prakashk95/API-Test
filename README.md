This project contains API testing of the website https://automationexercise.com/ using Postman.

**Tests Performed:**
The following API endpoints and scenarios were tested:

**1. Create User**

Successfully created a new user with valid data.

**2. Search User by Email**

Verified that a user exists by sending their email in the request.

**3. Verify Login**

Tested login functionality with valid credentials.

**4. Verify Login Without Password**

Checked system behavior when login is attempted with a missing password.

**5. Verify Login with Wrong Credentials**

Ensured that the API correctly rejects invalid login attempts.

**6. Delete Account**

Successfully deleted a registered user account and verified the response.

**7. Search Products**

Tested the product search functionality by keyword and validated response structure.

**8. Get All Products**

Tested the API endpoint to retrieve a complete list of all available products. Verified that the response contains a 200 status code and a properly structured JSON array with product details like ID, name, price, brand, and category


**Tools Used:**

**Postman** – For designing and running API tests

**JavaScript (Postman test scripts)** – For assertions and validations

**Chai Assertion Library** – Built into Postman for expressive tests

**Repository Contents**

**Postman_collection.json** – Exported Postman collection with all requests and test scripts

**README.md** – Documentation of test cases and setup

**Screenshots (optional)** – To demonstrate test results (can be added to a /screenshots folder)

**How to Run the Tests**
1. Open Postman
2. Import the postman_collection.json file
3. Set up required environment variables if needed
4. Run the collection using Collection Runner or manually
