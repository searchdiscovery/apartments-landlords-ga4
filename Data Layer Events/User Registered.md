# User Registered

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({
  "event": "sign_up",
  "detailed_event": "User Registered",
    "user_data": {
        "user_id": "<user_id>",
        "user_type": "<user_type>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|user_data.user_id|string|The id of the user currently logged in to the site, if the site offers authentication and the user is authenticated.|123456, abc123|||||||
|user_data.user_type|string|Captures the type associated with the user \(i.e. guest, registered, prime, etc\).|employee, guest, agent, customer|||||||




