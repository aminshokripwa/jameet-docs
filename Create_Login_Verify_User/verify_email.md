
# Verify Email

request

```http request
GET https://api.jameet.com/api/user/verify-email/{{Code emailed}}/{{User email}}
Content-Type: application/json
server-key: {{apikey}}

```

> If the code is entered correctly

Response

```http request
{
    "resp": true,
    "message": "Welcome successfully validated..."
}
```