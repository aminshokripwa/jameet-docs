# update data profile]

request

```http request
PUT https://api.jameet.com/api/user/update-data-profile
Content-Type: application/json
server-key: {{apikey}}
jmt-token: {{token}}

{
    "user": "{{user}}",
    "description": "{{description}}",
    "fullname": "{{fullname}}",
    "phone": "{{phone}}"
}

```

Response

```http request
{
    "resp": true,
    "message": "updated profile"
}
```