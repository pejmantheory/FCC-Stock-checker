# Stock Price Checker
<img width="1012" alt="Screenshot 2023-06-17 at 6 20 56 AM" src="https://github.com/pejmantheory/FCC-Stock-checker/assets/81389644/f55f85d2-92e0-4e4a-891f-f2a87c870311">
http://localhost:3000/

SET NODE_ENV to test without quotes and set DB to your MongoDB connection string
Complete the project in routes/api.js or by creating a handler/controller
You will add any security features to server.js
You will create all of the functional tests in tests/2_functional-tests.js
Note Privacy Considerations: Due to the requirement that only 1 like per IP should be accepted, you will have to save IP addresses. It is important to remain compliant with data privacy laws such as the General Data Protection Regulation. One option is to get permission to save the user's data, but it is much simpler to anonymize it. For this challenge, remember to anonymize IP addresses before saving them to the database. If you need ideas on how to do this, you may choose to hash the data, truncate it, or set part of the IP address to 0.

Write the following tests in tests/2_functional-tests.js:

Viewing one stock: GET request to /api/stock-prices/
Viewing one stock and liking it: GET request to /api/stock-prices/
Viewing the same stock and liking it again: GET request to /api/stock-prices/
Viewing two stocks: GET request to /api/stock-prices/
Viewing two stocks and liking them: GET request to /api/stock-prices/
