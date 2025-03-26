# Principles

The Relaxx v8.1.0 API is a REST API solution and attempts to conform to the RESTful design principles.

* The API Key is required to be passed in HTTP Request Headers (x-api-key).
* The request and response data is sent as JSON (HTTP Content-Type header = application/json).
* All connections must be made over HTTPS, not HTTP.
* The Date and Time data in the API request/response is in the UTC 00:00 format. This means that the date and time in offer details, offer time slots, etc., are shown as per the UTC 00:00 date and time.

**Developer agreement**

By using Relaxx v8.1.0 third-party API, you agree to our terms of service.
