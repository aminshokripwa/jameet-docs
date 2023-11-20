
# Create New Post

request

```http request
POST https://api.jameet.com/api/post/create-new-post
Content-Type: application/json
server-key: {{apikey}}
jmt-token: {{token}}

form-data
imagePosts      "Image"
type_privacy    1 Or 0
comment         "description"

```

> Create New Post

Response

```http request
{
    "resp": true,
    "message": "Posted"
}
```