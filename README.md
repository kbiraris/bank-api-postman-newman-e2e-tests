# Bank API E2E Tests
## Overview

This Postman collection tests the fund transfer workflow between accounts in the Bank API. It includes two main scenarios:
1. Successful Transfer – Creates all necessary resources and completes the transfer successfully.
2. Insufficient Funds – Attempts a transfer when the source account has insufficient balance.

The collection validates:
1. Response Format – Ensure valid JSON
2. Required Objects – All mandatory fields exist
3. Field Data Types - number, string, boolean, array
4. Business Logic – Values like balance, currency, status are correct
5. Conditional Handling – Store variables for downstream requests
6. Arrays / Collections – Each element has expected data
7. Response time
8. Header validation
9. Schema validation
