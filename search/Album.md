---
order: 93
icon: image
---

# Search Albums

+++ Request

HTTP [!badge variant="info" text="POST"]

```
https://saavnpro.ga/api/album/search
```
CURL

```bash
curl -X POST 'https://saavnpro.ga/api/search' \
-H 'content-type: application/json'
-D '{search: "romantic hits", type: "album"}'

```

+++ Response

```json
in_progress: "try later"
```
+++

| Payload Key                           | Required                              |
|---------------------------------------|---------------------------------------|
| [!badge variant="info" text="search"] | [!badge variant="danger" text="True"] |
| [!badge variant="info" text="type"]   | [!badge variant="danger" text="True"] |

!!!info Example payload

Send your data like below to get the results:

 ```json
{
  "search": "romantic hits",
  "type": "album"
}
```
!!!