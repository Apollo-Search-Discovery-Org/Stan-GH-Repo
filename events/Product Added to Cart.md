# Product Added to Cart

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Product Added to Cart",
    "cart": {
        "additionContext": "<additionContext>"
    },
    "product": [
        {
            "price": {
                "sellingPrice": "<sellingPrice>"
            },
            "productInfo": {
                "name": "<name>"
            }
        }
    ]
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|additionContext|string|Conveys the context of a cart addition. |PLP, PDP, Wishlist, Registry|||||||
|sellingPrice|string|String representation of the price paid after coupons or discounts. Positive. Up to two decimal places for cents. No currency symbol.|200, 29.99, 50, 0|^[0-9]*(\.[0-9]{1,2})?$||||||
