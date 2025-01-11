
- **Query Parameters**:
coin (Required): One of bitcoin, matic-network, ethereum.
## Testing

You can test the API endpoints using Postman or any HTTP client.

- **Example requests:**

1. Get stats for Bitcoin:

- **GET:** http://localhost:3000/stats?coin=bitcoin

2. Get the standard deviation of Bitcoin price:

- **GET:** http://localhost:3000/deviation?coin=bitcoin
