# Create User

request

```http request
POST https://api.jameet.com/api/user
Content-Type: application/json
server-key: {{apikey}}

{
    "username": "{{username}}",
    "fullname": "{{fullname}}",
    "email": "{{email}}",
    "password": "{{password}}"
}
```

> An email containing a confirmation code will be sent to the user, and the user's account will be activated by entering this code.

Response

```http request
{
    "resp": true,
    "message": "User created"
}

```