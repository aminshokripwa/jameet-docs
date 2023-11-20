# Renew Login

request

```http request
POST https://api.jameet.com/api/auth/renew-login
Content-Type: application/json
server-key: {{apikey}}
jmt-token: {{token}}

```

> Send token as jmt-token in Header

Response

```http request
{
    "resp": true,
    "message": "User created"
}
```