# Get All Posts

request

```http request
GET https://api.jameet.com/api/post/get-all-posts
Content-Type: application/json
server-key: {{apikey}}
jmt-token: {{token}}

```

> Show all user's posts

Response

```http request
{
    "resp": true,
    "message": "Get All Post",
    "posts": [
        {
            "post_uid": "xxxxxx-xxxxxx-xxxxxx-xxxxxx-xxxxxx",
            "is_comment": 1,
            "type_privacy": "1",
            "created_at": "2021-11-18T16:02:19.000Z",
            "person_uid": "xxxxxx-xxxxxx-xxxxxx-xxxxxx-xxxxxx",
            "app": 1,
            "username": "thisUser",
            "avatar": null,
            "images": "image.png",
            "count_comment": 1,
            "count_likes": 0,
            "is_like": 0
        }
    ]
}
```