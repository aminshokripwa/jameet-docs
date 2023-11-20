# Get User Chat List

request

```http request
POST https://api.jameet.com/api/chat/get-list-chat-by-user
Content-Type: application/json
server-key: {{apikey}}
jmt-token: {{token}}

```

> Get all user chat list

Response

```http request
{
    "resp": true,
    "message": "All Messages list by user",
    "listChat": [
        {
            "uid_list_chat": "xxxxxx-xxxxxx-xxxxxx-xxxxxx-xxxxxx",
            "source_uid": "xxxxxx-xxxxxx-xxxxxx-xxxxxx-xxxxxx",
            "target_uid": "xxxxxx-xxxxxx-xxxxxx-xxxxxx-xxxxxx",
            "last_message": "message",
            "updated_at": "2021-11-15T08:56:14.000Z",
            "username": "username",
            "avatar": "avatar-default.png"
        }
    ]
}
```