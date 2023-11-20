# Create new story

request

```http request
POST https://api.jameet.com/api/story/create-new-story
Content-Type: application/json
server-key: {{apikey}}
jmt-token: {{token}}

form-data

imageStory      "Image"

```

Response

```http request
{
    "resp": true,
    "message": "new story"
}
```