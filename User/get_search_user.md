# get search user

request

```http request
GET https://api.jameet.com/api/user/get-search-user/{{User}}
Content-Type: application/json
server-key: {{apikey}}
jmt-token: {{token}}

```

Response

```http request
{
    "resp": true,
    "message": "User finded",
    "userFind": [
        {
            "uid": "xxxxxx-xxxxxx-xxxxxx-xxxxxx-xxxxxx",
            "fullname": "fullname",
            "avatar": "avatar-default.png",
            "username": "username"
        },
        {
            "uid": "xxxxxx-xxxxxx-xxxxxx-xxxxxx-xxxxxx",
            "fullname": "fullname",
            "avatar": "avatar-default.png",
            "username": "username"
        }
    ]
}
```