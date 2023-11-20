# Add new comment

request

```http request
POST https://api.jameet.com/api/post/add-new-comment
Content-Type: application/json
server-key: {{apikey}}
jmt-token: {{token}}

{
    "uidPost": "uidPost",
    "comment": "description"
}

```

> uidPost post ID

Response

```http request
{
    "resp": true,
    "message": "New comment"
}
```