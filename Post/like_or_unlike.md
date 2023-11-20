# Like or unlike post

request

```http request
POST https://api.jameet.com/api/post/like-or-unlike-post
Content-Type: application/json
server-key: {{apikey}}
jmt-token: {{token}}

{
    "uidPost": "{{Uid.Post}}",
    "uidPerson": "{{Uid.Person}}",
}

```

> uidPerson user for this post uidPost

Response

```http request
{
    "resp": true,
    "message": "like"
}
```