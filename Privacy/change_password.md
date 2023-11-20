#Change password

request

```http request
PUT https://api.jameet.com/api/user/change-password
Content-Type: application/json
server-key: {{apikey}}
jmt-token: {{token}}

{
        "currentPassword" : "",
        "newPassword" : ""
}
```

Response

```http request
{

}
```