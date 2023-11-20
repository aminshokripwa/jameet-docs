# Save Post by user

request

```http request
POST https://api.jameet.com/api/post/add-new-comment
Content-Type: application/json
server-key: {{apikey}}
jmt-token: {{token}}

{
    "post_uid": "{{Uid.Post}}"
}

```

> Save Post by its uid

Response

```http request
{
    "resp": true,
    "message": "Posted save"
}
```