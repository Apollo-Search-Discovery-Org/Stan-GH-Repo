# CTA Link Clicked

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "CTA Link Clicked",
    "linkInfo": {
        "linkRegion": "<linkRegion>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|linkRegion|string|Indicates the region on page for a clicked link within the hierarchy [Site > Page > Region > Container > linkID]|Top Nav, Footer Nav, Hero, Recommended, Also Shopped, Also Bought|||||||
