# Checkout Started

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ ecommerce: null });  // Clear the previous ecommerce object.
dataLayer.push({
  "event": "begin_checkout",
  "detailed_event": "Checkout Started",
    "ecommerce": {
        "currency": "<currency>",
        "items": [
            {
                "affiliation": "<affiliation>",
                "item_id": "<item_id>",
                "item_name": "<item_name>",
                "price": <price>
            }
        ],
        "value": <value>
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|ecommerce.currency|string|The currency, in 3-letter ISO 4217 format.|USD|||||||
|ecommerce.items[n].affiliation|string|A product affiliation to designate a supplying company or brick and mortar store location.|Google Store|||||||
|ecommerce.items[n].item_id|string|Item ID \(context-specific\).The product primary ID \(SKU or UPC\)|SKU\_12345|||||||
|ecommerce.items[n].item_name|string|Item Name \(context-specific\).|jeggings|||||||
|ecommerce.items[n].price|number|The monetary price of the item, in units of the specified currency parameter.|9.99|||||||
|ecommerce.value|number|The monetary value of the event.|7.77, 239.55, 659|||||||




