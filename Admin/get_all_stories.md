# Get all stories

request

```http request
GET https://api.jameet.com/api/admin/get_all_story
Content-Type: application/json
server-key: {{apikey}}

```

Response

```http request
{
    "resp": true,
    "message": "Get All Stories(The last 2 months)",
    "allStories": [
        {
            "uid_story": "xxxxxx-xxxxxx-xxxxxx-xxxxxx-xxxxxx",
            "user_uid": "xxxxxx-xxxxxx-xxxxxx-xxxxxx-xxxxxx",
            "fullname": "fullname",
            "image": image.jpg
        }
    ]
}
```