# POST /zones/{zone_id}/purge_cache

**Resource:** [Zone](../resources/Zone.md)
**Purge Cached Content**
**Operation ID:** `zone-purge`

### Purge All Cached Content
Removes ALL files from Cloudflare's cache. All tiers can purge everything.
```
{"purge_everything": true}
```

### Purge Cached Content by URL
Granularly removes one or more files from Cloudflare's cache by specifying URLs. All tiers can purge by URL.

To purge files with custom cache keys, include the headers used to compute the cache key as in the example. If you have a device type or geo in your cache key, you will need to include the CF-Device-Type or CF-IPCountry headers. If you have lang in your cache key, you will need to include the Accept-Language header.

**NB:** When including the Origin header, be sure to include the **scheme** and **hostname**. The port number can be omitted if it is the default port (80 for http, 443 for https), but must be included otherwise.

Single file purge example with files:
```
{"files": ["http://www.example.com/css/styles.css", "http://www.example.com/js/index.js"]}
```
Single file purge example with url and header pairs:
```
{"files": [{url: "http://www.example.com/cat_picture.jpg", headers: { "CF-IPCountry": "US", "CF-Device-Type": "desktop", "Accept-Language": "zh-CN" }}, {url: "http://www.example.com/dog_picture.jpg", headers: { "CF-IPCountry": "EU", "CF-Device-Type": "mobile", "Accept-Language": "en-US" }}]}
```

### Purge Cached Content by Tag, Host or Prefix
Granularly removes one or more files from Cloudflare's cache either by specifying the host, the associated Cache-Tag, or a Prefix.

Flex purge with tags:
```
{"tags": ["a-cache-tag", "another-cache-tag"]}
```
Flex purge with hosts:
```
{"hosts": ["www.example.com", "images.example.com"]}
```
Flex purge with prefixes:
```
{"prefixes": ["www.example.com/foo", "images.example.com/bar/baz"]}
```

### Availability and limits
please refer to [purge cache availability and limits documentation page](https://developers.cloudflare.com/cache/how-to/purge-cache/#availability-and-limits).


## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | cache-purge_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Request to purge cached content successfull. |
| 4XX | Request to purge cached content failed. |

**Success Response Schema:**

[cache-purge_api-response-single-id](../schemas/cache-purge/cache-purge-api-response-single-id.md)

## Security

- **api_token**
- **api_email**
- **api_key**
