# Get comments by id post

request

```http request
GET https://api.jameet.com/api/post/get-comments-by-idpost/{{uidPost}}
Content-Type: application/json
server-key: {{apikey}}
jmt-token: {{token}}

```

> uidPerson user for this post uidPost

Response

```http request
{
    "resp": true,
    "message": "Get Commets",
    "comments": [
        {
            "uid": "xxxxxx-xxxxxx-xxxxxx-xxxxxx-xxxxxx",
            "comment": "yes do it",
            "is_like": 0,
            "created_at": "2022-11-18T16:02:19.000Z",
            "person_uid": "xxxxxx-xxxxxx-xxxxxx-xxxxxx-xxxxxx",
            "post_uid": "xxxxxx-xxxxxx-xxxxxx-xxxxxx-xxxxxx",
            "username": "username",
            "avatar": null
        }
    ]
}
```