# Get User By Id

request

```http request
GET https://api.jameet.com/api/user/get-User-By-Id
Content-Type: application/json
server-key: {{apikey}}
jmt-token: {{token}}

```

Response

```http request
{
    "resp": true,
    "message": "Get User by id",
    "user": {
        "uid": "xxxxxx-xxxxxx-xxxxxx-xxxxxx-xxxxxx",
        "fullname": "aaaa",
        "phone": null,
        "image": null,
        "cover": null,
        "birthday_date": null,
        "created_at": "2023-11-14T16:57:30.000Z",
        "username": "aaa",
        "description": null,
        "is_private": 1,
        "is_online": 0,
        "email": "zagma.co@gmail.com"
    },
    "posts": {
        "posters": 7,
        "friends": 0,
        "followers": 0
    }
}
```