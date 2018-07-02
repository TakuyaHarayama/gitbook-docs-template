# REST API

{% method %}
How to install GitBook API client.

{% sample lang="curl" %}
```bash
$curl -X GET https://api.keion.com/v1/members \
     -H "Content-Type: application/json" \
     -d @- << EOF
     {
       "access_token": "59xxxxxxxxxxxxxxxxxxxxxxxxxx",
       "space_id": "59xxxxxxxxxxxxxxxxxxxxxxxxxx",
       "limit": 1
     }
EOF
```

**Example Response**

```json
{
  "data": {
    "members": [
      {
        "id": "1",
        "name": "Yui Hirasawa",
        "job": "guitar",
        "sex": "female",
        "age": "18"
      }
    ]
  }
}
```
{% endmethod %}
