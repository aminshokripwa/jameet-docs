# Like or unlike comment

request

```http request
PUT https://api.jameet.com/api/post/like-or-unlike-comment
Content-Type: application/json
server-key: {{apikey}}
jmt-token: {{token}}

{
    "uidComment": "uid.Comment"
}

```

> uidComment Comment ID

Response

```http request
{
    "resp": true,
    "message": "like comment"
}
```