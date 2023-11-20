# Get all users data

request

```http request
GET https://api.jameet.com/api/admin/get_all_users_data
Content-Type: application/json
server-key: {{apikey}}

```

Response

```http request
{
    "resp": true,
    "message": "Get All Users",
    "allUsers": [
        {
            "person_uid": "xxxxxx-xxxxxx-xxxxxx-xxxxxx-xxxxxx",
            "username": "username",
            "description": description,
            "last_activity": last_activity,
            "email": "email",
            "cover": cover.jpg,
            "fullname": "fullname",
            "image": "avatar-default.png",
            "created_at": "2021-11-14T19:43:48.000Z",
            "updated_at": "2021-11-14T19:43:48.000Z",
        },
        {
            "person_uid": "xxxxxx-xxxxxx-xxxxxx-xxxxxx-xxxxxx",
            "username": "username",
            "description": description,
            "last_activity": last_activity,
            "email": "email",
            "cover": cover.jpg,
            "fullname": "fullname",
            "image": "avatar-default.png",
            "created_at": "2021-11-15T19:43:48.000Z",
            "updated_at": "2021-11-15T19:43:48.000Z",
        }
    ]
}
```