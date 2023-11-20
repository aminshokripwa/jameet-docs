# update image profile

request

```http request
PUT https://api.jameet.com/api/user/update-image-profile
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
    "message": "Updated Profile"
}
```