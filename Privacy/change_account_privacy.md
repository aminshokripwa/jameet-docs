#hange account privacy

request

```http request
PUT https://api.jameet.com/api/user/change-account-privacy
Content-Type: application/json
server-key: {{apikey}}
jmt-token: {{token}}

```

Response

```http request
{
    "resp": true,
    "message": "Account changed successfully"
}
```