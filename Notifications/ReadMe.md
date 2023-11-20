# Notification

request

```http request
GET https://api.jameet.com/api/notification/get-notification-by-user
Content-Type: application/json
server-key: {{apikey}}
jmt-token: {{token}}

```

>Types of notifications
1. Somebody Following current user
2. Somebody Likes story of current user
3. Somebody Follow back current user


Response

```http request
{
    "resp": true,
    "message": "Get Notifications",
    "notificationsdb": [
        {
            "uid_notification": "xxxxxx-xxxxxx-xxxxxx-xxxxxx-xxxxxx",
            "type_notification": "2",
            "created_at": "2022-11-18T16:28:31.000Z",
            "user_uid": "xxxxxx-xxxxxx-xxxxxx-xxxxxx-xxxxxx",
            "username": "username",
            "followers_uid": "xxxxxx-xxxxxx-xxxxxx-xxxxxx-xxxxxx",
            "follower": "username",
            "avatar": null,
            "post_uid": "xxxxxx-xxxxxx-xxxxxx-xxxxxx-xxxxxx",
        }
    ]
}
```