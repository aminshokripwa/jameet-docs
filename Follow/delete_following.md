# Delete followers

request

```http request
DELETE https://api.jameet.com/api/user/delete-following/{{uid_friend}}
Content-Type: application/json
server-key: {{apikey}}
jmt-token: {{token}}

```

Response

```http request
{
    "resp": true,
    "message": "Deleted friend"
}
```