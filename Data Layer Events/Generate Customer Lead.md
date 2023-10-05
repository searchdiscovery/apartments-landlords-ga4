# Generate Customer Lead

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "generate_customer_lead",
  "detailed_event": "Generate Customer Lead",
    "event_data": {
        "number_units": "<number_units>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|event_data.number_units|string|The number of units associated with a lead submission|10|||||||




