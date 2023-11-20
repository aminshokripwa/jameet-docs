#Update cover

request

```http request
PUT https://api.jameet.com/api/user/update-cover
Content-Type: application/json
server-key: {{apikey}}
jmt-token: {{token}}

form-data
imagePosts      "Image"
```

Response

```http request
{
    "resp": true,
    "message": "Updated Cover"
}
```