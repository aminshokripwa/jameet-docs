# get another user by id

request

```http request
GET https://api.jameet.com/api/user/get-another-user-by-id/{{User.uid}}
Content-Type: application/json
server-key: {{apikey}}
jmt-token: {{token}}

```

Response

```http request
{
    "resp": true,
    "message": "Get Another User by id",
    "anotherUser": {
        "uid": "xxxxxx-xxxxxx-xxxxxx-xxxxxx-xxxxxx",
        "fullname": "fullname",
        "phone": null,
        "image": "avatar-default.png",
        "cover": null,
        "birthday_date": null,
        "created_at": "2023-11-14T19:43:48.000Z",
        "username": "username",
        "description": null,
        "is_private": 0,
        "is_online": 0,
        "email": "email"
    },
    "analytics": {
        "posters": 0,
        "friends": 0,
        "followers": 0
    },
    "postsUser": [],
    "is_friend": 0,
    "isPendingFollowers": 0
}
```