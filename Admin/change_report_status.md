#hange report status

request

```http request
PUT https://api.jameet.com/api/admin/change_report_status/{{report.Id}}
Content-Type: application/json
server-key: {{apikey}}

```

Response

```http request
{
    "resp": true,
    "message": "Changes applied"
}
```