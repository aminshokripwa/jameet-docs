# Login User

request

```http request
POST https://api.jameet.com/api/auth-login
Content-Type: application/json
server-key: {{apikey}}

{
    "email": "",
    "password": ""
}
```

Response

```http request
{
    "resp": true,
    "message": "Welcome to JAMEET",
    "token": "User token"
}
```