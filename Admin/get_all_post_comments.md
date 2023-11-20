# Get all post comments

request

```http request
GET https://api.jameet.com/api/admin/get_all_post_comment/{{post.Id}}
Content-Type: application/json
server-key: {{apikey}}

```

Response

```http request
{
    "resp": true,
    "message": "Get All Comments",
    "allComments": []
}
```