This endpoint logs in a user using their email and password.

### How it works

- Submit a POST request with JSON body:
```json
{
    "email": "user@example.com",
    "password": "your-password"
  }
```
- If successful, you'll receive a JWT token in the response.

### Errors

- 401 Unauthorized: Invalid credentials.