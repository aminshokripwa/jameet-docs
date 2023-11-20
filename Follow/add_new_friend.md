# Add new friend

request

```http request
POST https://api.jameet.com/api/user/add-new-friend
Content-Type: application/json
server-key: {{apikey}}
jmt-token: {{token}}

{
    "uidFriend": "User.uid"
}

```

Response

```http request
{
    "resp": true,
    "message": "New friend"
}
```