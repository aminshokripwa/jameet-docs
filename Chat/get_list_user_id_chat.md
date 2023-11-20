# Get List user Id Chat

request

```http request
POST https://api.jameet.com/api/chat/get-all-message-by-user/{{target_uid}}
Content-Type: application/json
server-key: {{apikey}}
jmt-token: {{token}}

```

> Show list of chat for special target_uid

Response

```http request
{
    "resp": true,
    "message": "get all messages by user",
    "listMessage": [
        {
            "uid_messages": "xxxxxx-xxxxxx-xxxxxx-xxxxxx-xxxxxx",
            "source_uid": "xxxxxx-xxxxxx-xxxxxx-xxxxxx-xxxxxx",
            "target_uid": "xxxxxx-xxxxxx-xxxxxx-xxxxxx-xxxxxx",
            "message": "message",
            "created_at": "2023-11-15T08:56:14.000Z"
        },
        {
            "uid_messages": "xxxxxx-xxxxxx-xxxxxx-xxxxxx-xxxxxx",
            "source_uid": "xxxxxx-xxxxxx-xxxxxx-xxxxxx-xxxxxx",
            "target_uid": "xxxxxx-xxxxxx-xxxxxx-xxxxxx-xxxxxx",
            "message": "message",
            "created_at": "2021-11-15T08:56:09.000Z"
        }
    ]
}
```