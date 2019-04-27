#general
<!-- START_8de61d2bd6fce53f44bce349af68c309 -->
## Show the application dashboard.

> Example request:

```bash
curl -X GET -G "http://localhost/documentation" 
```

```javascript
const url = new URL("http://localhost/documentation");

let headers = {
    "Accept": "application/json",
    "Content-Type": "application/json",
}

fetch(url, {
    method: "GET",
    headers: headers,
})
    .then(response => response.json())
    .then(json => console.log(json));
```

> Example response:

```json
null
```

### HTTP Request
`GET documentation`


<!-- END_8de61d2bd6fce53f44bce349af68c309 -->
