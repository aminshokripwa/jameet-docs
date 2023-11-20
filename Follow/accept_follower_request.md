# accept follower request

request

```http request
POST https://api.jameet.com/api/user/accept-follower-request
Content-Type: application/json
server-key: {{apikey}}
jmt-token: {{token}}

{
    "uidFriend": "{{uid.Friend}}",
    //id of floowing by uidFriend
    "uidNotification": "{{uid.Notification}}"
}

```

Response

```http request
{

}
```