# External API Documentation

## 1. Exchange Rate API
* **Provider:** ExchangeRate-API
* **Method:** `GET /v6/{key}/latest/{base_currency}`
* **Key Field:** `conversion_rates`


**Sample Response:**
```json
{
  "result": "success",
  "base_code": "USD",
  "time_last_update_unix": 1770681602,
  "conversion_rates": {
    "USD": 1,
    "BRL": 5.1972,
    "EUR": 0.8406,
    "GBP": 0.7318,
    "...": "..." 
  }
}