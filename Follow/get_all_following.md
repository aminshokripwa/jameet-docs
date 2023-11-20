# Get all following

request

```http request
GET https://api.jameet.com/api/user/get-all-following
Content-Type: application/json
server-key: {{apikey}}
jmt-token: {{token}}

```

Response

```http request
{
    "resp": true,
    "message": "Get All Following",
    "followings": [
        {
            "uid_friend": "xxxxxx-xxxxxx-xxxxxx-xxxxxx-xxxxxx",
            "uid_user": "xxxxxx-xxxxxx-xxxxxx-xxxxxx-xxxxxx",
            "date_friend": "2021-11-18T18:08:14.000Z",
            "username": "username",
            "fullname": "fullname",
            "avatar": "avatar-default.png"
        }
    ]
}
```