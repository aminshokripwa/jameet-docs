# Get all posts

request

```http request
GET https://api.jameet.com/api/admin/get_all_post_comment/{{Post.ID}}
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