# Get Post by idPerson

request

```http request
GET https://api.jameet.com/api/post/get-post-by-idPerson
Content-Type: application/json
server-key: {{apikey}}
jmt-token: {{token}}

```

> Show all user's posts url for images : https://api.jameet.com/{{images}}

Response

```http request
{
    "resp": true,
    "message": "Get Posts by IdPerson",
    "post": [
        {
            "uid": "xxxxxx-xxxxxx-xxxxxx-xxxxxx-xxxxxx",
            "is_comment": 1,
            "type_privacy": "1",
            "app": 1,
            "created_at": "2022-11-18T16:02:19.000Z",
            "images": "image.jpg,image.png,image.webp"
        }
    ]
}
```